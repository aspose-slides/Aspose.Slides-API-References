---
title: GetAttributeNode()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott névvel rendelkező XmlAttribute-ot.
type: docs
weight: 248
url: /hu/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metódus

Visszaadja a megadott névvel rendelkező [XmlAttribute](../../xmlattribute/)-t.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum neve, amelyet le akarunk kérni. Ez egy kvalifikált név. A megfelelő csomópont **get_Name** értékéhez van illesztve. |

### Visszatérési érték

A megadott [XmlAttribute](../../xmlattribute/) vagy **nullptr**, ha nem található megfelelő attribútum.

## XmlElement::GetAttributeNode(String, String) metódus

Visszaadja a megadott helyi névvel és névtér URI-val rendelkező [XmlAttribute](../../xmlattribute/)-t.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

A megadott [XmlAttribute](../../xmlattribute/) vagy **nullptr**, ha nem található megfelelő attribútum.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)