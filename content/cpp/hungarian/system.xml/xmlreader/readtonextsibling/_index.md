---
title: ReadToNextSibling()
second_title: Aspose.Slides C++ API referencia
description: Előre lépteti az XmlReader-t a megadott minősített névvel rendelkező következő testvér elemre.
type: docs
weight: 924
url: /hu/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) metódus


Előre lépteti a [XmlReader](../)-t a megadott minősített névvel rendelkező következő testvér elemre.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A testvér elem minősített neve, amelyre lépni kíván. |

### Visszatérési érték

**true** ha megfelelő testvér elem található; egyébként **false**. Ha nem található megfelelő testvér elem, akkor a [XmlReader](../) a szülő elem záró címkéjére ([XmlReader::get_NodeType](../get_nodetype/) érték [XmlNodeType::EndElement](../../xmlnodetype/)) kerül.

## XmlReader::ReadToNextSibling(String, String) metódus


Előre lépteti a [XmlReader](../)-t a megadott helyi névvel és névtér-URI-vel rendelkező következő testvér elemre.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A testvér elem helyi neve, amelyre lépni kíván. |
| namespaceURI | [String](../../../system/string/) | A testvér elem névtér-URI-ja, amelyre lépni kíván. |

### Visszatérési érték

**true** ha megfelelő testvér elem található; egyébként **false**. Ha nem található megfelelő testvér elem, akkor a [XmlReader](../) a szülő elem záró címkéjére ([XmlReader::get_NodeType](../get_nodetype/) érték [XmlNodeType::EndElement](../../xmlnodetype/)) kerül.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)