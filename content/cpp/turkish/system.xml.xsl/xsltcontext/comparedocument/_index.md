---
title: CompareDocument()
second_title: Aspose.Slides for C++ API Referansı
description: Bir türetilmiş sınıfta geçersiz kılındığında, iki belgenin temel Uniform Resource Identifiers (URIs) değerlerini, XSLT işlemcisi tarafından belgelerin yüklenme sırasına göre karşılaştırır (yani, XslTransform sınıfı).
type: docs
weight: 53
url: /tr/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) method

Bir türetilmiş sınıfta geçersiz kılındığında, iki belgenin temel Uniform Resource Identifiers (URIs) değerlerini, XSLT işlemcisi tarafından belgelerin yüklenme sırasına göre karşılaştırır (yani, [XslTransform](../../xsltransform/) sınıfı).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Karşılaştırılacak ilk belgenin temel URI'si. |
| nextbaseUri | [String](../../../system/string/) | Karşılaştırılacak ikinci belgenin temel URI'si. |

### Dönüş Değeri

İki temel URI'nin göreceli sırasını tanımlayan bir tam sayı değeri: -1, **baseUri** **nextbaseUri**'den önce geliyorsa; 0, iki temel URI aynıysa; ve 1, **baseUri** **nextbaseUri**'den sonra geliyorsa.

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XsltContext](../)
* Ad alanı [System::Xml::Xsl](../../)
* Kütüphane [Aspose.Slides](../../../)