---
title: SelectChildren()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vybere všechny podřízené uzly aktuálního uzlu, které mají odpovídající XPathNodeType.
type: docs
weight: 833
url: /cs/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metoda

Vybere všechny podřízené uzly aktuálního uzlu, které mají odpovídající XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType podřízených uzlů. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) obsahující vybrané uzly.

## XPathNavigator::SelectChildren(String, String) metoda

Vybere všechny podřízené uzly aktuálního uzlu, které mají specifikovaný lokální název a URI jmenného prostoru.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokální název podřízených uzlů. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru podřízených uzlů. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) obsahující vybrané uzly.

## Viz také

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNodeIterator](../../xpathnodeiterator/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)