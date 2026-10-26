---
title: UriComponents
second_title: Aspose.Slides для C++ справочник API
description: Представляет компоненты URI.
type: docs
weight: 3212
url: /ru/system/uricomponents/
---
## UriComponents enum

Представляет компоненты URI.

```cpp
enum class UriComponents
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Scheme | 1 | Данные Scheme. |
| UserInfo | 2 | Данные UserInfo. |
| Host | 4 | Данные Host. |
| Port | 8 | Данные Port. |
| SchemeAndServer | n/a | Данные Scheme, Host и Port. |
| Path | 16 | Данные LocalPath. |
| Query | 32 | Данные Query. |
| PathAndQuery | n/a | Данные LocalPath и Query. |
| HttpRequestUrl | n/a | Данные Scheme, Host, Port, Query и LocalPath. |
| Fragment | 64 | Данные Fragment. |
| AbsoluteUri | n/a | Данные Scheme, Host, Port, Quer, LocalPath и Fragment. |
| StrongPort | 128 | Данные Port; если данные порта отсутствуют в [Uri](../uri/) и порту по умолчанию был назначен Scheme, возвращается порт по умолчанию; если порта по умолчанию нет, возвращается -1. |
| HostAndPort | n/a | Данные Host и Port; если данные порта отсутствуют в [Uri](../uri/) и порту по умолчанию был назначен Scheme, возвращается порт по умолчанию. Если порта по умолчанию нет, возвращается -1. |
| StrongAuthority | n/a | Данные UserInfo, Host и Port.Если данные порта отсутствуют в [Uri](../uri/) и порту по умолчанию был назначен Scheme, возвращается порт по умолчанию.Если порта по умолчанию нет, возвращается -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Указывает, что разделитель должен быть включён. |
| SerializationInfoString | n/a | Полный контекст [Uri](../uri/), необходимый для сериализаторов [Uri](../uri/). Контекст включает область IPv6. |

## См. также

* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)