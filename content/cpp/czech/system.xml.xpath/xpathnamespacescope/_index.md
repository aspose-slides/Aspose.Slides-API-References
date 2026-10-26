---
title: XPathNamespaceScope
second_title: Aspose.Slides pro C++ API Reference
description: Definuje rozsah jmenných prostorů.
type: docs
weight: 144
url: /cs/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum

Definuje rozsah jmenných prostorů.

```cpp
enum class XPathNamespaceScope
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| All | 0 | Vrací všechny jmenné prostory definované v rozsahu aktuálního uzlu. To zahrnuje jmenný prostor **xmlns:xml**, který je vždy deklarován implicitně. Pořadí vrácených jmenných prostorů není definováno. |
| ExcludeXml | 1 | Vrací všechny jmenné prostory definované v rozsahu aktuálního uzlu, vyjma jmenného prostoru **xmlns:xml**. Jmenný prostor **xmlns:xml** je vždy deklarován implicitně. Pořadí vrácených jmenných prostorů není definováno. |
| Local | 2 | Vrací všechny jmenné prostory, které jsou definovány lokálně v aktuálním uzlu. |

## Viz také

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)