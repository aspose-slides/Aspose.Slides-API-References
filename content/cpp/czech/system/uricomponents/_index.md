---
title: UriComponents
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje komponenty URI.
type: docs
weight: 3251
url: /cs/system/uricomponents/
---
## UriComponents enum

Represents URI components.

```cpp
enum class UriComponents
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Scheme | 1 | Data Scheme. |
| UserInfo | 2 | Data UserInfo. |
| Host | 4 | Data Host. |
| Port | 8 | Data Port. |
| SchemeAndServer | n/a | Data Scheme, Host a Port. |
| Path | 16 | Data LocalPath. |
| Query | 32 | Data Query. |
| PathAndQuery | n/a | Data LocalPath a Query. |
| HttpRequestUrl | n/a | Data Scheme, Host, Port, Query a LocalPath. |
| Fragment | 64 | Data Fragment. |
| AbsoluteUri | n/a | Data Scheme, Host, Port, Quer, LocalPath a Fragment. |
| StrongPort | 128 | Data Port; pokud data portu nejsou přítomna v [Uri](../uri/) a výchozí port byl přiřazen ke Scheme, vrátí se výchozí port; pokud neexistuje výchozí port, vrátí se -1. |
| HostAndPort | n/a | Data Host a Port; pokud data portu nejsou přítomna v [Uri](../uri/) a výchozí port byl přiřazen ke Scheme, vrátí se výchozí port. Pokud neexistuje výchozí port, vrátí se -1. |
| StrongAuthority | n/a | Data UserInfo, Host a Port. Pokud nejsou data portu v [Uri](../uri/) a výchozí port byl přiřazen ke Scheme, vrátí se výchozí port. Pokud neexistuje výchozí port, vrátí se -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Určuje, že oddělovač má být zahrnut. |
| SerializationInfoString | n/a | Úplný kontext [Uri](../uri/), který je potřebný pro [Uri](../uri/) Serializers. Kontext zahrnuje rozsah IPv6. |

## Viz také

* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)