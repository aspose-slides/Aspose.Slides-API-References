---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 508
url: /tr/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Klonlanan şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Klonlanan şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Return Value

Yeni oluşturulan [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Yeni şekil, *sourceShape* öğesinin genişlik ve yüksekliğini korur.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, puan cinsinden. |

### Return Value

Yeni oluşturulan [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Klonlanan şekil, orijinalin konum ve boyutunu korur.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |

### Return Value

Yeni oluşturulan [IShape](../../ishape/).

## See Also

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [IShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)