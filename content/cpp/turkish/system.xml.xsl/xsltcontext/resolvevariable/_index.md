---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, bir değişken referansını çözer ve değişkeni temsil eden bir IXsltContextVariable döndürür.
type: docs
weight: 14
url: /tr/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) yöntemi


Türetilmiş bir sınıfta geçersiz kılındığında, bir değişken referansını çözer ve değişkeni temsil eden bir [IXsltContextVariable](../../ixsltcontextvariable/) döndürür.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Değişkenin [XPath](../../../system.xml.xpath/) ifadesinde göründüğü önek. |
| name | [String](../../../system/string/) | Değişkenin adı. |

### Dönüş Değeri

Çalışma zamanında değişkeni temsil eden bir [IXsltContextVariable](../../ixsltcontextvariable/).

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)