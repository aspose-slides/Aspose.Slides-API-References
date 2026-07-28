---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API referencia
description: Feloldja a névtér előtagját az aktuális elem hatókörében.
type: docs
weight: 612
url: /hu/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String&) metódus

Megoldja egy névtér előtagját az aktuális elem hatókörében.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az előtag, amelynek a névtér URI-ját fel szeretné oldani. Az alapértelmezett névtér egyezéséhez üres karakterláncot adjon meg. Ennek a karakterláncnak nem kell atomizáltnak lennie. |

### Visszatérési érték

A névtér URI, amelyre az előtag mutat, vagy **nullptr**, ha nem található megfelelő előtag.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)