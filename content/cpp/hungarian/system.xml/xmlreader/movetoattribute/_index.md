---
title: MoveToAttribute()
second_title: Aspose.Slides a C++ API hivatkozásához
description: "Ha egy származtatott osztályban felül van definiálva, a megadott XmlReader::get_Name értékkel rendelkező attribútumra lép."
type: docs
weight: 625
url: /hu/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) metódus


Ha egy leszármazott osztályban felül van definiálva, a megadott [XmlReader::get_Name](../get_name/) értékkel rendelkező attribútumra lép.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum minősített neve. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlReader::MoveToAttribute(String, String) metódus


Ha egy leszármazott osztályban felül van definiálva, a megadott [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékekkel rendelkező attribútumra lép.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum helyi neve. |
| ns | [String](../../../system/string/) | Az attribútum névtér-URI-ja. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlReader::MoveToAttribute(int32_t) metódus


Ha egy leszármazott osztályban felül van definiálva, a megadott indexű attribútumra lép.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)