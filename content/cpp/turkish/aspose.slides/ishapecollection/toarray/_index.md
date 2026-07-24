---
title: ToArray()
second_title: C++ için Aspose.Slides API Referansı
description: Tüm şekilleri içeren bir dizi oluşturur ve döndürür.
type: docs
weight: 287
url: /tr/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metodu

Tüm şekilleri içeren bir dizi oluşturur ve döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### Dönüş Değeri

[IShape](../../ishape/) nesnelerinden oluşan bir dizi.

## IShapeCollection::ToArray(int32_t, int32_t) metodu

Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Döndürülecek ilk şeklin indeksi. |
| count | **int32_t** | Döndürülecek şekil sayısı. |

### Dönüş Değeri

[IShape](../../ishape/) nesnelerinden oluşan bir dizi.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)