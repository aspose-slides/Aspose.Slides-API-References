---
title: MoveToChild()
second_title: Aspose.Slides for C++ API referencia
description: Áthelyezi az XPathNavigator-t a megadott helyi névvel és névtér-URI-val rendelkező gyermekcsomópontra.
type: docs
weight: 690
url: /hu/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Áthelyezi a [XPathNavigator](../)-t a megadott helyi névvel és névtér-URI-val rendelkező gyermekcsomópontra.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A gyermekcsomópontra való áthelyezéshez megadandó helyi név. |
| namespaceURI | [String](../../../system/string/) | A gyermekcsomópontra való áthelyezéshez megadandó névtér-URI. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződik a gyermekcsomópontra; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## XPathNavigator::MoveToChild(XPathNodeType) method


Áthelyezi a [XPathNavigator](../)-t a megadott XPathNodeType-ú gyermekcsomópontra.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | A gyermekcsomópontra való áthelyezéshez megadandó XPathNodeType. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződik a gyermekcsomópontra; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)