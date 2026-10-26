---
title: SelectAncestors()
second_title: Aspose.Slides pro C++ API Reference
description: Vybere všechny předky aktuálního uzlu, které mají odpovídající XPathNodeType.
type: docs
weight: 846
url: /cs/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metoda

Vybere všechny předky aktuálního uzlu, které mají odpovídající XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType předků. |
| matchSelf | **bool** | Pro zahrnutí kontextového uzlu do výběru použijte **true**; jinak **false**. |

### Návratová hodnota

Objekt [XPathNodeIterator](../../xpathnodeiterator/), který obsahuje vybrané uzly. Vrácené uzly jsou v opačném pořadí dokumentu.

## XPathNavigator::SelectAncestors(String, String, bool) metoda

Vybere všechny předky aktuálního uzlu, které mají zadaný lokální název a URI jmenného prostoru.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokální název předků. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru předků. |
| matchSelf | **bool** | Pro zahrnutí kontextového uzlu do výběru použijte **true**; jinak **false**. |

### Návratová hodnota

Objekt [XPathNodeIterator](../../xpathnodeiterator/), který obsahuje vybrané uzly. Vrácené uzly jsou v opačném pořadí dokumentu.

## Viz také

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)