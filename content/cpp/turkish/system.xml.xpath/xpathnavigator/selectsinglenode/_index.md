---
title: SelectSingleNode()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen XPath sorgusunu kullanarak XPathNavigator içinde tek bir düğüm seçer.
type: docs
weight: 781
url: /tr/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metodu

Belirtilen [XPath](../../) sorgusunu kullanarak [XPathNavigator](../) içinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) ifadesini temsil eden bir [String](../../../system/string/). |

### Dönüş Değeri

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde sorgu sonucu yoksa **nullptr**.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metodu

[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesiyle namespace ön eklerini çözmek için belirtilen [XPath](../../) sorgusunu kullanarak [XPathNavigator](../) nesnesinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) ifadesini temsil eden bir [String](../../../system/string/). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../) sorgusunda namespace ön eklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde sorgu sonucu yoksa **nullptr**.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metodu

Belirtilen [XPathExpression](../../xpathexpression/) nesnesini kullanarak [XPathNavigator](../) içinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Derlenmiş [XPath](../../) sorgusunu içeren bir [XPathExpression](../../xpathexpression/) nesnesi. |

### Dönüş Değeri

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde sorgu sonucu yoksa **nullptr**.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)