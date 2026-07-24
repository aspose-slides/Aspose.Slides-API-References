---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API Referansı
description: Derived sınıfta geçersiz kılındığında, verilen bağlam için beyaz boşluk düğümlerinin korunup korunmayacağını veya kaldırılıp kaldırılmayacağını değerlendirir.
type: docs
weight: 40
url: /tr/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) yöntemi

When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Geçerli bağlamda korunacak veya kaldırılacak beyaz boşluk düğümü. |

### Dönüş Değeri

**true** eğer beyaz boşluk korunacaksa; **false** eğer beyaz boşluk kaldırılacaksa.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Sınıf [XsltContext](../)
* İsim Alanı [System::Xml::Xsl](../../)
* Kütüphane [Aspose.Slides](../../../)