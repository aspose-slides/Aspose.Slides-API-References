---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API referencia
description: Áthelyezi az XPathNavigator-t a dokumentum sorrendjében a megadott helyi névvel és névtér-URI-val rendelkező elemre.
type: docs
weight: 703
url: /hu/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metódus

A [XPathNavigator](../) áthelyezi a dokumentum sorrendjében a megadott helyi névvel és névtér-URI-val rendelkező elemre.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az elem helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az elem névtér-URI-ja. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződött; egyébként **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metódus

A [XPathNavigator](../) áthelyezi a dokumentum sorrendjében a megadott helyi névvel és névtér-URI-val rendelkező elemre, a megadott határig.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az elem helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az elem névtér-URI-ja. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | A [XPathNavigator](../) objektum, amely az elem határán helyezkedik el, és a jelenlegi [XPathNavigator](../) nem lépi át, miközben a következő elemet keresi. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződött; egyébként **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metódus

A [XPathNavigator](../) áthelyezi a dokumentum sorrendjében a megadott XPathNodeType következő elemére.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Az elem XPathNodeType-ja. Az XPathNodeType nem lehet [XPathNodeType::Attribute](../../xpathnodetype/) vagy [XPathNodeType::Namespace](../../xpathnodetype/). |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződött; egyébként **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metódus

A [XPathNavigator](../) áthelyezi a dokumentum sorrendjében a megadott XPathNodeType következő elemére, a megadott határig.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Az elem XPathNodeType-ja. Az XPathNodeType nem lehet [XPathNodeType::Attribute](../../xpathnodetype/) vagy [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | A [XPathNavigator](../) objektum, amely az elem határán helyezkedik el, és a jelenlegi [XPathNavigator](../) nem lépi át, miközben a következő elemet keresi. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen áthelyeződött; egyébként **false**.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)