---
title: LookupPrefix()
second_title: Aspose.Slides C++ API referenciája
description: Megkeresi a megadott névtér URI-hez deklarált előtagot.
type: docs
weight: 131
url: /hu/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) metódus

Megkeresi a megadott névtér URI-hez deklarált előtagot.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | A névtér, amelyhez az előtagot meg kell oldani. |

### Visszatérési érték

A megfelelő előtag. Ha nincs leképezett előtag, a metódus [String::Empty](../../../system/string/empty/) értéket ad vissza. Ha null érték van megadva, akkor **nullptr** kerül visszaadásra.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNamespaceManager](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)