---
title: SelectDescendants()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vybere všechny potomkové uzly aktuálního uzlu, které mají odpovídající XPathNodeType.
type: docs
weight: 859
url: /cs/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metoda


Vybere všechny potomkové uzly aktuálního uzlu, které mají odpovídající XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType potomkových uzlů. |
| matchSelf | **bool** | **true** pro zahrnutí kontextového uzlu do výběru; jinak **false**. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) obsahující vybrané uzly.

## XPathNavigator::SelectDescendants(String, String, bool) metoda


Vybere všechny potomkové uzly aktuálního uzlu s určeným lokálním názvem a URI jmenného prostoru.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokální název potomkových uzlů. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru potomkových uzlů. |
| matchSelf | **bool** | **true** pro zahrnutí kontextového uzlu do výběru; jinak **false**. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) obsahující vybrané uzly.

## Viz také

* Výčet [XPathNodeType](../../xpathnodetype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNodeIterator](../../xpathnodeiterator/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)