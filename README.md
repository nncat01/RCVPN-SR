[**English**](https://github.com/nncat01/RCVPN-SR/blob/main/README.en.md) | **Русский**

# RCVPN-SR

Автоматическая генерация RULE-SET файлов `.list` для Proxy/VPN клиента [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118)

В качестве исходных файлов используются sing-box `.srs` файлы из репозитория [hydraponique/roscomvpn-routing](https://github.com/hydraponique/roscomvpn-routing)

Сделано на основе парсера от [Master-Yoba/shadowrocket-rules](https://github.com/Master-Yoba/shadowrocket-rules)

По идее, также совместимо с [Surge](https://apps.apple.com/us/app/surge-5/id1442620678)
#
Ниже приведены готовые конфигурации, являющиеся адаптацией конфигураций из [hydraponique/roscomvpn-routing](https://github.com/hydraponique/roscomvpn-routing) под Shadowrocket, есливы не ходите заморачиватся с созданием своей

| Конфиг маршрутизации | Публичный DNS |
|-----------|-----------|
| [Default](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_A.conf) | AdGuard DNS + Yandex DNS |
| [Default](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_C.conf) | Cloudflare DNS + Yandex DNS |
| [Default](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_G.conf) | Google DNS + Yandex DNS |
| [Whitelist](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN-WL_D_A.conf) | AdGuard DNS + Yandex DNS |
| [Whitelist](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN-WL_D_C.conf) | Cloudflare DNS + Yandex DNS |
| [Whitelist](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN-WL_D_G.conf) | Google DNS + Yandex DNS |
