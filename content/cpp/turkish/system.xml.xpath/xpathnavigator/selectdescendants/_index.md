---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün, eşleşen bir XPathNodeType değerine sahip tüm alt düğümlerini seçer.
type: docs
weight: 859
url: /tr/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metodu

Geçerli düğümün, eşleşen bir XPathNodeType değerine sahip tüm alt düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Alt düğümlerin XPathNodeType değeri. |
| matchSelf | **bool** | **true** seçimin içinde bağlam düğümünü dahil etmek için; aksi takdirde **false**. |

### Dönüş Değeri

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::SelectDescendants(String, String, bool) metodu

Geçerli düğümün, belirtilen yerel ada ve ad alanı URI'sine sahip tüm alt düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alt düğümlerin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Alt düğümlerin ad alanı URI'si. |
| matchSelf | **bool** | **true** seçimin içinde bağlam düğümünü dahil etmek için; aksi takdirde **false**. |

### Dönüş Değeri

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/).

## Ayrıca

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathNodeIterator](../../xpathnodeiterator/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)