---
title: Select()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen XPath ifadesini kullanarak bir düğüm kümesi seçer.
type: docs
weight: 794
url: /tr/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) method

Belirtilen [XPath](../../) ifadesini kullanarak bir düğüm kümesi seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Bir [XPath](../../) ifadesini temsil eden [String](../../../system/string/). |

### Dönüş Değeri

Seçilen düğüm kümesini işaret eden bir [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method

Ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesiyle birlikte belirtilen [XPath](../../) ifadesini kullanarak bir düğüm kümesi seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Bir [XPath](../../) ifadesini temsil eden [String](../../../system/string/). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

Seçilen düğüm kümesini gösteren bir [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method

Belirtilen [XPathExpression](../../xpathexpression/) kullanarak bir düğüm kümesi seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Derlenmiş [XPath](../../) sorgusunu içeren bir [XPathExpression](../../xpathexpression/) nesnesi. |

### Dönüş Değeri

Seçilen düğüm kümesini gösteren bir [XPathNodeIterator](../../xpathnodeiterator/).

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)