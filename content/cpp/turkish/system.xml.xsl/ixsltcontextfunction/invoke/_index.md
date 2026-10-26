---
title: Invoke()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bağlamda verilen argümanlarla fonksiyonu çağırmak için yöntemi sağlar.
type: docs
weight: 53
url: /tr/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

Verilen bağlamda verilen argümanlarla fonksiyonu çağırmak için yöntemi sağlar.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Fonksiyon çağrısı için XSLT bağlamı. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Fonksiyon çağrısının argümanları. Her argüman dizide bir öğedir. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Fonksiyon çağrısı için bağlam düğümü. |

### Dönüş Değeri

Fonksiyonun dönüş değerini temsil eden bir [Object](../../../system/object/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [XsltContext](../../xsltcontext/)
* Sınıf [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Sınıf [IXsltContextFunction](../)
* Ad alanı [System::Xml::Xsl](../../)
* Kütüphane [Aspose.Slides](../../../)