---
title: ToArray()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm şekilleri içeren bir dizi oluşturur ve döndürür.
type: docs
weight: 326
url: /tr/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metod

Tüm şekilleri içeren bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Dönüş Değeri

Bir dizi [IShape](../../ishape/) nesnesi.

## ShapeCollection::ToArray(int32_t, int32_t) metod

Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Döndürülecek ilk şeklin dizini. |
| count | **int32_t** | Döndürülecek şekil sayısı. |

### Dönüş Değeri

Bir dizi [IShape](../../ishape/) nesnesi.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [ShapeCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)