---
title: XPathNamespaceScope
second_title: Aspose.Slides för C++ API-referens
description: Definierar namnrymdsomfånget.
type: docs
weight: 144
url: /sv/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum

Definierar namnrymdsomfånget.

```cpp
enum class XPathNamespaceScope
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| All | 0 | Returnerar alla namnrymder som definieras i omfattningen för den aktuella noden. Detta inkluderar namnrymden **xmlns:xml** som alltid deklareras implicit. Ordningen på de returnerade namnrymderna är inte definierad. |
| ExcludeXml | 1 | Returnerar alla namnrymder som definieras i omfattningen för den aktuella noden, exklusive namnrymden **xmlns:xml**. Namnrymden **xmlns:xml** deklareras alltid implicit. Ordningen på de returnerade namnrymderna är inte definierad. |
| Local | 2 | Returnerar alla namnrymder som definieras lokalt på den aktuella noden. |

## Se även

* Namnrymd [System::Xml::XPath](../)
* Bibliotek [Aspose.Slides](../../)