---
title: SetAttributeNode()
second_title: Aspose.Slides C++ API referencia
description: Hozzáadja a megadott XmlAttribute-ot.
type: docs
weight: 261
url: /hu/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) metódus


Hozzáadja a megadott [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | [XmlAttribute](../../xmlattribute/) csomó, amelyet ehhez az elemhez tartozó attribútumgyűjteményhez adunk hozzá. |

### Visszatérési érték

Ha az attribútum felülír egy ugyanazzal a névvel rendelkező meglévő attribútumot, akkor a régi [XmlAttribute](../../xmlattribute/) kerül visszaadásra; egyébként **nullptr** kerül visszaadásra.

## XmlElement::SetAttributeNode(String, String) metódus


Hozzáadja a megadott [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

A hozzáadandó [XmlAttribute](../../xmlattribute/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [XmlElement](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)