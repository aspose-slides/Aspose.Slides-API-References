---
title: LookupNamespace()
second_title: Aspose.Slides C++ API Referencia
description: Feloldja a névtér előtagját az aktuális elem hatókörében.
type: docs
weight: 404
url: /hu/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) metódus

Feloldja a névtér előtagját az aktuális elem hatókörében.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az előtag, amelynek a namespace URI-ját fel szeretné oldani. Az alapértelmezett namespace-hoz illesztéshez adjon meg egy üres karakterláncot. Ennek a karakterláncnak nem kell atomizáltnak lennie. |

### Visszatérési érték

A namespace URI, amelyhez az előtag tartozik, vagy **nullptr**, ha nincs megfelelő előtag.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)