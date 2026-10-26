---
title: GetCacheControlLength()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indexten başlayan bir dizeyi CacheControlHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 456
url: /tr/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metot

Belirtilen indexten başlayan verilen bir dizeyi [CacheControlHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için bir başlangıç konumu. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Ayrıştırılmış nesneye eklenmesi gereken bir değer. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğu, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [CacheControlHeaderValue](../)
* İsim Uzayı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)