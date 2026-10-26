---
title: SelectNodes()
second_title: Aspose.Slides for C++ API Referansı
description: XPath ifadesiyle eşleşen bir düğüm listesini seçer.
type: docs
weight: 365
url: /tr/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) metot

[XPath](../../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) ifadesi. |

### Dönüş Değeri

Bir [XmlNodeList](../../xmlnodelist/), [XPath](../../../system.xml.xpath/) sorgusuyla eşleşen düğümlerin bir koleksiyonunu içerir.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metot

[XPath](../../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer. [XPath](../../../system.xml.xpath/) ifadesinde bulunan tüm ön ekler, sağlanan [XmlNamespaceManager](../../xmlnamespacemanager/) kullanılarak çözülür.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) ifadesi. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) ifadesindeki ön ekler için ad alanlarını çözmek üzere kullanılacak bir [XmlNamespaceManager](../../xmlnamespacemanager/). |

### Dönüş Değeri

Bir [XmlNodeList](../../xmlnodelist/), [XPath](../../../system.xml.xpath/) sorgusuyla eşleşen düğümlerin bir koleksiyonunu içerir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNodeList](../../xmlnodelist/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Sınıf [XmlNamespaceManager](../../xmlnamespacemanager/)
* AdAlanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)