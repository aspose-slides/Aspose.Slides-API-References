---
title: LookupPrefix()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a megadott névtér URI-hez deklarált előtagot.
type: docs
weight: 417
url: /hu/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) method


Visszaadja a megadott névtér URI-hez deklarált előtagot.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | A névtér URI, amelynek az előtagját fel kell oldani. |

### Visszatérési érték

Egy [String](../../../system/string/), amely a megadott névtér URI-hez rendelt névtérelőtagot tartalmaz; egyébként [String::Empty](../../../system/string/empty/), ha a megadott névtér URI-hez nincs előtag rendelve. A visszaadott [String](../../../system/string/) atomizált.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)