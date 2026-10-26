---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API referenciája
description: A XmlReader-t a megadott minősített névvel rendelkező következő leszármazott elemre állítja előre.
type: docs
weight: 911
url: /hu/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metódus


A [XmlReader](../)-t a megadott minősített névvel rendelkező következő leszármazott elemre állítja előre.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A lépni kívánt elem minősített neve. |

### Visszatérési érték

**true**, ha megtalálható a megfelelő leszármazott elem; egyébként **false**. Ha nem található megfelelő gyermekelem, a [XmlReader](../) az elem záró címkéjén ([XmlReader::get_NodeType](../get_nodetype/) értéke [XmlNodeType::EndElement](../../xmlnodetype/)) helyezkedik el. Ha a [XmlReader](../) nem egy elemen van pozicionálva, amikor a [XmlReader::ReadToDescendant(String)](./) lett meghívva, ez a metódus **false** értékkel tér vissza, és a [XmlReader](../) pozíciója nem változik.

## XmlReader::ReadToDescendant(String, String) metódus


A [XmlReader](../)-t a megadott helyi névvel és névtér URI-vel rendelkező következő leszármazott elemre állítja.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az elem helyi neve, amelyre lépni kíván. |
| namespaceURI | [String](../../../system/string/) | Az elemnek a kívánt névtér URI-ja. |

### Visszatérési érték

**true**, ha megtalálható a megfelelő leszármazott elem; egyébként **false**. Ha nem található megfelelő gyermekelem, a [XmlReader](../) az elem záró címkéjén ([XmlReader::get_NodeType](../get_nodetype/) értéke [XmlNodeType::EndElement](../../xmlnodetype/)) helyezkedik el. Ha a [XmlReader](../) nem egy elemen van pozicionálva, amikor a [XmlReader::ReadToDescendant(String,String)](./) lett meghívva, ez a metódus **false** értékkel tér vissza, és a [XmlReader](../) pozíciója nem változik.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)