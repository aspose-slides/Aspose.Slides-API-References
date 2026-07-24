---
title: GetRangeItemLength()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indeksden geçirilen bir dizeyi RangeItemHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 92
url: /tr/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) metod

Belirtilen indeksden geçirilen bir dizeyi [RangeItemHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için bir başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğunu döndürür, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [RangeItemHeaderValue](../)
* Ad alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)