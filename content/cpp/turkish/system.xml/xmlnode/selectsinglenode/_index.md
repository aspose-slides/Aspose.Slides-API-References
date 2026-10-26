---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API Referansı
description: XPath ifadesiyle eşleşen ilk XmlNode öğesini seçer.
type: docs
weight: 352
url: /tr/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) yöntemi


İlk [XmlNode](../) öğesini [XPath](../../../system.xml.xpath/) ifadesiyle eşleşen olarak seçer.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) ifadesi. |

### Dönüş Değeri

Eşleşen [XPath](../../../system.xml.xpath/) sorgusuyla eşleşen ilk [XmlNode](../) veya eşleşen bir düğüm bulunamazsa **nullptr**.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) yöntemi


İlk [XmlNode](../) öğesini [XPath](../../../system.xml.xpath/) ifadesiyle eşleşen olarak seçer. [XPath](../../../system.xml.xpath/) ifadesinde bulunan tüm önekler, sağlanan [XmlNamespaceManager](../../xmlnamespacemanager/) kullanılarak çözülür.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) ifadesi. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) ifadesindeki önekler için ad alanlarını çözmek amacıyla kullanılacak bir [XmlNamespaceManager](../../xmlnamespacemanager/). |

### Dönüş Değeri

Eşleşen [XPath](../../../system.xml.xpath/) sorgusuyla eşleşen ilk [XmlNode](../) veya eşleşen bir düğüm bulunamazsa **nullptr**.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamespaceManager](../../xmlnamespacemanager/)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)