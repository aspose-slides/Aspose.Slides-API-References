---
title: UriComponents
second_title: Aspose.Slides för C++ API-referens
description: Representerar URI-komponenter.
type: docs
weight: 3251
url: /sv/system/uricomponents/
---
## UriComponents enum

Representerar URI-komponenter.

```cpp
enum class UriComponents
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Scheme | 1 | Scheme-data. |
| UserInfo | 2 | UserInfo-data. |
| Host | 4 | Host-data. |
| Port | 8 | Port-data. |
| SchemeAndServer | n/a | Scheme-, Host- och Port-data. |
| Path | 16 | LocalPath-data. |
| Query | 32 | Query-data. |
| PathAndQuery | n/a | LocalPath- och Query-data. |
| HttpRequestUrl | n/a | Scheme-, Host-, Port-, Query- och LocalPath-data. |
| Fragment | 64 | Fragment-data. |
| AbsoluteUri | n/a | Scheme-, Host-, Port-, Quer-, LocalPath- och Fragment-data. |
| StrongPort | 128 | Port-data; om portdata inte finns i [Uri](../uri/) och en standardport har tilldelats Scheme, returneras standardporten; om det inte finns någon standardport returneras -1. |
| HostAndPort | n/a | Host- och Port-data; om portdata inte finns i [Uri](../uri/) och en standardport har tilldelats Scheme, returneras standardporten. Om det inte finns någon standardport returneras -1. |
| StrongAuthority | n/a | UserInfo-, Host- och Port-data.Om ingen portdata finns i [Uri](../uri/) och en standardport har tilldelats Scheme, returneras standardporten.Om det inte finns någon standardport returneras -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Anger att avgränsaren ska inkluderas. |
| SerializationInfoString | n/a | Den kompletta [Uri](../uri/)-kontexten som behövs för [Uri](../uri/)-serializers. Kontexten inkluderar IPv6-omfånget. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)