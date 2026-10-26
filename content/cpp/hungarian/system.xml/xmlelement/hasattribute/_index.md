---
title: HasAttribute()
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy az aktuális csomópont rendelkezik-e a megadott névvel rendelkező attribútummal.
type: docs
weight: 300
url: /hu/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metódus

Megállapítja, hogy az aktuális csomópont rendelkezik-e a megadott névvel rendelkező attribútummal.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum kereséséhez megadott név. Ez egy minősített név. A megfelelő csomópont **get_Name** értékével van összehasonlítva. |

### Return Value

**true** ha az aktuális csomópont rendelkezik a megadott attribútummal; egyébként **false**.

## XmlElement::HasAttribute(String, String) metódus

Megállapítja, hogy az aktuális csomópont rendelkezik-e a megadott helyi névvel és névtér URI-val rendelkező attribútummal.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum kereséséhez megadott helyi név. |
| namespaceURI | [String](../../../system/string/) | Az attribútum kereséséhez megadott névtér URI. |

### Return Value

**true** ha az aktuális csomópont rendelkezik a megadott attribútummal; egyébként **false**.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)