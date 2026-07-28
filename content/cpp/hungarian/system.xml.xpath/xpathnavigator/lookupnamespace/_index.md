---
title: LookupNamespace()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott előtaghoz tartozó névtér URI-t.
type: docs
weight: 404
url: /hu/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metódus

Visszaadja a megadott előtaghoz tartozó névtér URI-t.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az az előtag, amelynek névtér URI-ját szeretné feloldani. Az alapértelmezett névtérhez való illesztéshez adja meg a [String::Empty](../../../system/string/empty/) értéket. |

### Visszatérési érték

A [String](../../../system/string/) amely tartalmazza a megadott névtér előtaghoz hozzárendelt névtér URI-t; **nullptr**, ha a megadott előtaghoz nincs hozzárendelt névtér URI. A visszaadott [String](../../../system/string/) atomizált.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)