---
title: RegisterPrefix()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI için WebRequest türemini kaydeder.
type: docs
weight: 92
url: /tr/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metot


Belirtilen URI için [WebRequest](../) türevi kaydeder.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI veya URI öneki. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | [WebRequest](../) sınıfının yeni örneklerini oluşturur. |

### Dönüş Değeri

Belirtilen URI için [WebRequest](../) türevi başarıyla kaydedildiğinde doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IWebRequestCreate](../../iwebrequestcreate/)
* Sınıf [WebRequest](../)
* İsim Uzayı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)