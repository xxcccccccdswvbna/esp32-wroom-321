# esp32-wroom-321

ct1/
├── ct1.yaml                          # 主入口
├── base/
│   ├── wifi.yaml
│   ├── web.yaml
│   ├── sensors.yaml
│   ├── text_sensors.yaml
│   ├── outputs.yaml
│   ├── lights.yaml
│   ├── buttons.yaml
│   ├── physical_keys.yaml
│   ├── globals_extra.yaml
│   ├── offline_script.yaml
│   └── mqtt.yaml                     # 巴法云
├── ble/
│   ├── core.yaml
│   ├── globals.yaml
│   ├── script.yaml
│   ├── tracker.yaml                  # 含巴法云状态上报
│   ├── dev3.yaml
│   └── dev_controls.yaml             # 含带ID的button
└── .github/
    └── workflows/
        └── build.yml                 # CI/CD
