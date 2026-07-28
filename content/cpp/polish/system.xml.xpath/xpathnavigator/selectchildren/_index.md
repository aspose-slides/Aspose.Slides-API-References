---
title: SelectChildren()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wybiera wszystkie węzły potomne bieżącego węzła, które mają pasujący XPathNodeType.
type: docs
weight: 833
url: /pl/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) method

Wybiera wszystkie węzły potomne bieżącego węzła, które mają pasujący XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType węzłów potomnych. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły.

## XPathNavigator::SelectChildren(String, String) method

Wybiera wszystkie węzły potomne bieżącego węzła, które mają określoną nazwę lokalną i URI przestrzeni nazw.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa węzłów potomnych. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw węzłów potomnych. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) zawierający wybrane węzły.

## Zobacz także

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNodeIterator](../../xpathnodeiterator/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)