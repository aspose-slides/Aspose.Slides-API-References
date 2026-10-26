---
title: WriteNode()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, okuyucudan yazıcıya her şeyi kopyalar ve okuyucuyu bir sonraki kardeşin başlangıcına taşır.
type: docs
weight: 430
url: /tr/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) metot


Derived bir sınıfta geçersiz kılındığında, okuyucudan yazıcıya her şeyi kopyalar ve okuyucuyu bir sonraki kardeşin başlangıcına taşır.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Okunacak [XmlReader](../../xmlreader/). |
| defattr | **bool** | **true** varsayılan nitelikleri [XmlReader](../../xmlreader/)'den kopyalamak için; aksi takdirde **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) metot


XPathNavigator nesnesinden yazıcıya her şeyi kopyalar. XPathNavigator'un konumu değişmeden kalır.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Kopyalanacak XPathNavigator. |
| defattr | **bool** | **true** varsayılan nitelikleri kopyalamak için; aksi takdirde **false**. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)