---
title: RemoveAttributeNode()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a megadott XmlAttribute-ot.
type: docs
weight: 274
url: /hu/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metódus


Eltávolítja a megadott [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | A [XmlAttribute](../../xmlattribute/) csomópont, amelyet el kell távolítani. Ha az eltávolított attribútumnak alapértelmezett értéke van, azt azonnal helyettesítik. |

### Visszatérési érték

A eltávolított [XmlAttribute](../../xmlattribute/) vagy **nullptr**, ha **oldAttr** nem attribútum csomópontja a [XmlElement](../)-nak.

## XmlElement::RemoveAttributeNode(String, String) metódus


Eltávolítja a [XmlAttribute](../../xmlattribute/)-t, amelyet a helyi név és a névtér URI határoz meg. (Ha az eltávolított attribútumnak alapértelmezett értéke van, azt azonnal helyettesítik).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

A eltávolított [XmlAttribute](../../xmlattribute/) vagy **nullptr**, ha a [XmlElement](../) nem rendelkezik a megfelelő attribútum csomóponttal.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)