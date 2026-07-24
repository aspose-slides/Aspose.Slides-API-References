---
title: GetRangeItemListLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen konumdan geçirilen bir dizeyi RangeItemHeaderValue sınıfı örneklerinin koleksiyonuna dönüştürür.
type: docs
weight: 79
url: /tr/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) metodu

Geçilen bir dizeyi belirtilen konumdan RangeItemHeaderValue sınıfı örneklerinin koleksiyonuna dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Ayrıştırılmış koleksiyonun atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dize uzunluğu, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ICollection](../../../system.collections.generic/icollection/)
* Sınıf [RangeItemHeaderValue](../)
* Ad alanı [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)