---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, bir işlev referansını çözer ve işlevi temsil eden bir IXsltContextFunction döndürür. IXsltContextFunction, işlevin dönüş değerini yürütme zamanında almak için kullanılır.
type: docs
weight: 27
url: /tr/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metot

Türetilmiş bir sınıfta geçersiz kılındığında, bir işlev referansını çözer ve işlevi temsil eden bir [IXsltContextFunction](../../ixsltcontextfunction/) döndürür. [IXsltContextFunction](../../ixsltcontextfunction/), işlevin dönüş değerini yürütme zamanında almak için kullanılır.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | [XPath](../../../system.xml.xpath/) ifadesinde göründüğü gibi işlevin öneki. |
| name | [String](../../../system/string/) | İşlevin adı. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Çözülmekte olan işlev için argüman türlerinin bir dizisi. Bu, aynı ada sahip yöntemler arasında seçim yapmanızı sağlar (örneğin, aşırı yüklenmiş yöntemler). |

### Dönüş Değeri

Bir [IXsltContextFunction](../../ixsltcontextfunction/) temsil eden işlev.

## İlgili

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)