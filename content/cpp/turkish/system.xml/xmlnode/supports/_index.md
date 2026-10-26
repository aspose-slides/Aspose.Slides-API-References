---
title: Supports()
second_title: Aspose.Slides for C++ API Referansı
description: DOM uygulamasının belirli bir özelliği uygulayıp uygulamadığını test eder.
type: docs
weight: 482
url: /tr/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metodu


Belirli bir özelliğin DOM uygulaması tarafından uygulanıp uygulanmadığını test eder.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Test edilecek özelliğin paket adı. Bu ad büyük/küçük harfe duyarlı değildir. |
| version | [String](../../../system/string/) | Test edilecek paket adının sürüm numarası. Sürüm belirtilmemişse (null), özelliğin herhangi bir sürümünün desteklenmesi yöntemin true dönmesine neden olur. |

### Dönüş Değeri

**true** eğer özellik belirtilen sürümde uygulanmışsa; aksi takdirde **false**.

## Açıklamalar



Aşağıdaki tablo **true** döndüren kombinasyonları açıklar. 

| Özellik | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)