---
title: SelectAncestors()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli düğümün eşleşen bir XPathNodeType'a sahip tüm ata düğümlerini seçer.
type: docs
weight: 846
url: /tr/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metod

Mevcut düğümün eşleşen bir XPathNodeType'a sahip tüm ata düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Atalar düğümlerinin XPathNodeType'ı. |
| matchSelf | **bool** | Seçime bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### Dönüş Değeri

[XPathNodeIterator](../../xpathnodeiterator/) içinde seçilen düğümler bulunur. Döndürülen düğümler ters belge sırasındadır.

## XPathNavigator::SelectAncestors(String, String, bool) metod

Mevcut düğümün belirtilen yerel adı ve ad alanı URI'sine sahip tüm ata düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Atalar düğümlerinin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Atalar düğümlerinin ad alanı URI'si. |
| matchSelf | **bool** | Seçime bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### Dönüş Değeri

[XPathNodeIterator](../../xpathnodeiterator/) içinde seçilen düğümler bulunur. Döndürülen düğümler ters belge sırasındadır.

## İlgili

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)