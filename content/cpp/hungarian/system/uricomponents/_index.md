---
title: UriComponents
second_title: Aspose.Slides for C++ API hivatkozás
description: Az URI komponenseket reprezentálja.
type: docs
weight: 3251
url: /hu/system/uricomponents/
---
## UriComponents enum

Az URI komponenseket reprezentálja.

```cpp
enum class UriComponents
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Scheme | 1 | A Scheme adat. |
| UserInfo | 2 | A UserInfo adat. |
| Host | 4 | A Host adat. |
| Port | 8 | A Port adat. |
| SchemeAndServer | n/a | A Scheme, Host és Port adat. |
| Path | 16 | A LocalPath adat. |
| Query | 32 | A Query adat. |
| PathAndQuery | n/a | A LocalPath és Query adat. |
| HttpRequestUrl | n/a | A Scheme, Host, Port, Query és LocalPath adat. |
| Fragment | 64 | A Fragment adat. |
| AbsoluteUri | n/a | A Scheme, Host, Port, Quer, LocalPath és Fragment adat. |
| StrongPort | 128 | A Port adat; ha a port adat nincs jelen a [Uri](../uri/)-ban és egy alapértelmezett port lett hozzárendelve a Scheme-hez, az alapértelmezett port kerül visszaadásra; ha nincs alapértelmezett port, -1 kerül visszaadásra. |
| HostAndPort | n/a | A Host és Port adat; ha a port adat nincs jelen a [Uri](../uri/)-ban és egy alapértelmezett port lett hozzárendelve a Scheme-hez, az alapértelmezett port kerül visszaadásra. Ha nincs alapértelmezett port, -1 kerül visszaadásra. |
| StrongAuthority | n/a | A UserInfo, Host és Port adat. Ha nincs port adat a [Uri](../uri/)-ban és egy alapértelmezett port lett hozzárendelve a Scheme-hez, az alapértelmezett port kerül visszaadásra. Ha nincs alapértelmezett port, -1 kerül visszaadásra. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Megadja, hogy a határolót be kell vonni. |
| SerializationInfoString | n/a | A teljes [Uri](../uri/) kontextus, amely a [Uri](../uri/) Serializers számára szükséges. A kontextus tartalmazza az IPv6 hatókört. |

## Lásd még

* Namespace [System](../)
* Library [Aspose.Slides](../../)