---
title: GetParam()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a névtérrel ellátott névhez társított paramétert.
type: docs
weight: 14
url: /hu/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) metódus

Visszaadja a névtérrel ellátott névhez társított paramétert.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A paraméter neve. [XsltArgumentList](../) nem ellenőrzi, hogy a megadott név érvényes helyi név-e; azonban a név nem lehet **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | A paraméterhez társított névtér URI. |

### Visszatérési érték

A paraméter objektum, vagy **nullptr**, ha nem található.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [String](../../../system/string/)
* Osztály [XsltArgumentList](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)