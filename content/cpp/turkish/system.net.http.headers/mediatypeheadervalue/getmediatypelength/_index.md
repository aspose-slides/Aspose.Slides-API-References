---
title: GetMediaTypeLength()
second_title: Aspose.Slides için C++ API Referansı
description: Geçilen bir dizeyi belirtilen indeksden itibaren MediaTypeHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 144
url: /tr/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) yöntemi

Belirtilen indeksden itibaren verilen bir dizeyi [MediaTypeHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | [MediaTypeHeaderValue](../) sınıfının örneklerini oluşturmak için kullanılan delege. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dize uzunluğunu döndürür, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [MediaTypeHeaderValue](../)
* İsim Alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)