---
title: SetAttribute()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a megadott névvel rendelkező attribútum értékét.
type: docs
weight: 222
url: /hu/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metódus

Beállítja a megadott névvel rendelkező attribútum értékét.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum neve, amelyet létre kell hozni vagy módosítani. Ez egy minősített név. Ha a név kettőspontot tartalmaz, akkor előtagra és helyi névre bontódik. |
| value | [String](../../../system/string/) | Az attribútumhoz beállítandó érték. |

## XmlElement::SetAttribute(String, String, String) metódus

Beállítja a megadott helyi névvel és névtér URI-val rendelkező attribútum értékét.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |
| value | [String](../../../system/string/) | Az attribútumhoz beállítandó érték. |

### Visszatérési érték

Az attribútum értéke.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)