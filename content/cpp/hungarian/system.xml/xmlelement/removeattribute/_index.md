---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API referencia
description: Eltávolít egy attribútumot név alapján.
type: docs
weight: 235
url: /hu/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metódus

Eltávolít egy attribútumot név alapján.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az eltávolítandó attribútum neve. Ez egy kvalifikált név. Az egyező csomópont **get_Name** értékével van összehasonlítva. |

## XmlElement::RemoveAttribute(String, String) metódus

Eltávolít egy attribútumot a megadott helyi névvel és névtér URI-val. (Ha az eltávolított attribútumnak van alapértelmezett értéke, azt azonnal helyettesíti).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az eltávolítandó attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az eltávolítandó attribútum névtér URI-ja. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)