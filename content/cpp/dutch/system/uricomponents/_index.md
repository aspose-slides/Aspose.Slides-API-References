---
title: UriComponents
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt URI-componenten voor.
type: docs
weight: 3251
url: /nl/system/uricomponents/
---
## UriComponents enum

Stelt URI-componenten voor.

```cpp
enum class UriComponents
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Scheme | 1 | De Scheme-gegevens. |
| UserInfo | 2 | De UserInfo-gegevens. |
| Host | 4 | De Host-gegevens. |
| Port | 8 | De Port-gegevens. |
| SchemeAndServer | n/a | De Scheme-, Host- en Port-gegevens. |
| Path | 16 | De LocalPath-gegevens. |
| Query | 32 | De Query-gegevens. |
| PathAndQuery | n/a | De LocalPath- en Query-gegevens. |
| HttpRequestUrl | n/a | De Scheme-, Host-, Port-, Query- en LocalPath-gegevens. |
| Fragment | 64 | De Fragment-gegevens. |
| AbsoluteUri | n/a | De Scheme-, Host-, Port-, Quer-, LocalPath- en Fragment-gegevens. |
| StrongPort | 128 | De Port-gegevens; als de port-gegevens niet aanwezig zijn in de [Uri](../uri/) en een standaardpoort is toegewezen aan de Scheme, wordt de standaardpoort geretourneerd; als er geen standaardpoort is, wordt -1 geretourneerd. |
| HostAndPort | n/a | De Host- en Port-gegevens; als de port-gegevens niet aanwezig zijn in de [Uri](../uri/) en een standaardpoort is toegewezen aan de Scheme, wordt de standaardpoort geretourneerd. Als er geen standaardpoort is, wordt -1 geretourneerd. |
| StrongAuthority | n/a | De UserInfo-, Host- en Port-gegevens. Als er geen port-gegevens zijn in de [Uri](../uri/) en een standaardpoort is toegewezen aan de Scheme, wordt de standaardpoort geretourneerd. Als er geen standaardpoort is, wordt -1 geretourneerd. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Specificeert dat de scheidingsteken moet worden opgenomen. |
| SerializationInfoString | n/a | De volledige [Uri](../uri/)-context die nodig is voor [Uri](../uri/)-serializers. De context omvat de IPv6-scope. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)