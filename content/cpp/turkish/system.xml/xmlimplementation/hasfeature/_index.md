---
title: HasFeature()
second_title: Aspose.Slides for C++ API Referansı
description: Belge Nesne Modeli (DOM) uygulamasının belirli bir özelliği uygulayıp uygulamadığını test eder.
type: docs
weight: 14
url: /tr/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) method


Belge [Object](../../../system/object/) Modeli (DOM) uygulamasının belirli bir özelliği uygulayıp uygulamadığını test eder.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Test edilecek özelliğin paket adı. Bu ad büyük/küçük harfe duyarlı değildir. |
| strVersion | const [String](../../../system/string/)\& | Test edilecek paket adının sürüm numarasıdır. Sürüm belirtilmemişse (**nullptr**), özelliğin herhangi bir sürümünün desteklenmesi yöntemin **true** döndürmesine neden olur. |

### Dönüş Değeri

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Açıklamalar



Aşağıdaki tablo, **HasFeature** yönteminin **true** dönmesine neden olan kombinasyonları gösterir. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlImplementation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)