---
title: UriComponents
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Reprezentuje elementy URI.
type: docs
weight: 3251
url: /pl/system/uricomponents/
---
## UriComponents enum

Reprezentuje elementy URI.

```cpp
enum class UriComponents
```

### Wartości

| Name | Value | Description |
| --- | --- | --- |
| Scheme | 1 | Dane Scheme. |
| UserInfo | 2 | Dane UserInfo. |
| Host | 4 | Dane Host. |
| Port | 8 | Dane Port. |
| SchemeAndServer | n/a | Dane Scheme, Host i Port. |
| Path | 16 | Dane LocalPath. |
| Query | 32 | Dane Query. |
| PathAndQuery | n/a | Dane LocalPath i Query. |
| HttpRequestUrl | n/a | Dane Scheme, Host, Port, Query i LocalPath. |
| Fragment | 64 | Dane Fragment. |
| AbsoluteUri | n/a | Dane Scheme, Host, Port, Quer, LocalPath i Fragment. |
| StrongPort | 128 | Dane Port; jeśli dane portu nie są obecne w [Uri](../uri/) i domyślny port został przypisany do Scheme, zwracany jest domyślny port; jeśli nie ma domyślnego portu, zwracane jest -1. |
| HostAndPort | n/a | Dane Host i Port; jeśli dane portu nie są obecne w [Uri](../uri/) i domyślny port został przypisany do Scheme, zwracany jest domyślny port. Jeśli nie ma domyślnego portu, zwracane jest -1. |
| StrongAuthority | n/a | Dane UserInfo, Host i Port. Jeśli brak danych portu w [Uri](../uri/) i domyślny port został przypisany do Scheme, zwracany jest domyślny port. Jeśli nie ma domyślnego portu, zwracane jest -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Określa, że separator powinien być włączony. |
| SerializationInfoString | n/a | Pełny kontekst [Uri](../uri/), który jest potrzebny dla Serializatorów [Uri](../uri/). Kontekst zawiera zakres IPv6. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)