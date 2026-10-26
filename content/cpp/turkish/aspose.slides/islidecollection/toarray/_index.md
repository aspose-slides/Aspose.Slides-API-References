---
title: ToArray()
second_title: Aspose.Slides için C++ API Referansı
description: Tüm slaytları içeren bir dizi oluşturur ve döndürür.
type: docs
weight: 92
url: /tr/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() metodu

Creates and returns an array with all slides in it.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Dönüş Değeri

Dizi [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) metodu

Creates and returns an array with all slides from the specified range in it.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Eklenecek ilk slaydın indeksi. |
| count | **int32_t** | Eklenecek slayt sayısı. |

### Dönüş Değeri

Dizi [ISlide](../../islide/)

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [ISlideCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)