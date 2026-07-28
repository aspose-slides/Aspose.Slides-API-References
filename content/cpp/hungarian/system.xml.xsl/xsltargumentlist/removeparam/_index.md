---
title: RemoveParam()
second_title: Aspose.Slides C++ API-referencia
description: Eltávolítja a paramétert az XsltArgumentList-ból.
type: docs
weight: 66
url: /hu/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metódus


Eltávolítja a paramétert a [XsltArgumentList](../)-ból.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Az eltávolítandó paraméter neve. [XsltArgumentList](../) nem ellenőrzi, hogy a megadott név érvényes helyi név-e; azonban a név nem lehet **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Az eltávolítandó paraméter névterének URI-ja. |

### Visszatérési érték

A paraméterobjektum vagy **nullptr**, ha nem található.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [String](../../../system/string/)
* Osztály [XsltArgumentList](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)