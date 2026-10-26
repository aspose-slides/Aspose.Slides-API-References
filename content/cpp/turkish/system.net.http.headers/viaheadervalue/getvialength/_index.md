---
title: GetViaLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksten verilen bir dizeyi ViaHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 131
url: /tr/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) metot

Geçilen bir dizeyi belirtilen indeksden [ViaHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Ayrıştırılmış bir nesnenin atanacağı örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dize uzunluğunu döndürür, aksi takdirde 0.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ViaHeaderValue](../)
* İsim Alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)