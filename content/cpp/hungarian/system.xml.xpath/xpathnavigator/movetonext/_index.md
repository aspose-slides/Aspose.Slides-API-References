---
title: MoveToNext()
second_title: Aspose.Slides C++ API-referencia
description: Ha egy származtatott osztályban felül van definiálva, a XPathNavigator a jelenlegi csomópont következő testvércsomópontjára mozgatja.
type: docs
weight: 586
url: /hu/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metódus


Ha egy származtatott osztályban felül van definiálva, a [XPathNavigator](../) a jelenlegi csomópont következő testvércsomópontjára mozgatja.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen a következő testvércsomópontra mozog; egyébként **false**, ha már nincs több testvércsomópont, vagy ha a [XPathNavigator](../) jelenleg egy attribútumcsomóponton van. Ha **false**, akkor a [XPathNavigator](../) pozíciója változatlan marad.

## XPathNavigator::MoveToNext(String, String) metódus


A [XPathNavigator](../) a megadott helyi névvel és névtér-URI-vel rendelkező következő testvércsomópontra mozgatja.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A következő testvércsomópont helyi neve, amelyre mozogni kell. |
| namespaceURI | [String](../../../system/string/) | A következő testvércsomópont névtér-URI-ja, amelyre mozogni kell. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen a következő testvércsomópontra mozog; **false**, ha már nincs több testvércsomópont, vagy ha a [XPathNavigator](../) jelenleg egy attribútumcsomóponton van. Ha **false**, akkor a [XPathNavigator](../) pozíciója változatlan marad.

## XPathNavigator::MoveToNext(XPathNodeType) metódus


A [XPathNavigator](../) a megadott XPathNodeType-nak megfelelő, a jelenlegi csomópont következő testvércsomópontjára mozgatja.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | A testvércsomópont XPathNodeType-ja, amelyre mozogni kell. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen a következő testvércsomópontra mozog; egyébként **false**, ha már nincs több testvércsomópont, vagy ha a [XPathNavigator](../) jelenleg egy attribútumcsomóponton van. Ha **false**, akkor a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)