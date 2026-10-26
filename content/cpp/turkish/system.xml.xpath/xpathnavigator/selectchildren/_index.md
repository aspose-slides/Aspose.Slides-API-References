---
title: SelectChildren()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün, eşleşen XPathNodeType değerine sahip tüm alt düğümlerini seçer.
type: docs
weight: 833
url: /tr/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metodu

Geçerli düğümün, eşleşen XPathNodeType değerine sahip tüm alt düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Alt düğümlerin XPathNodeType değeri. |

### Dönüş Değeri

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::SelectChildren(String, String) metodu

Geçerli düğümün, belirtilen yerel ada ve ad alanı URI'sine sahip tüm alt düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alt düğümlerin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Alt düğümlerin ad alanı URI'si. |

### Dönüş Değeri

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/).

## Ayrıca Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathNodeIterator](../../xpathnodeiterator/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)