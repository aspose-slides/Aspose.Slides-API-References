---
title: InsertClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 560
url: /tr/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metod

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanmış şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |
| x | **float** | Klonlanmış şeklin çerçevesinin x-koordinatı, nokta cinsinden. |
| y | **float** | Klonlanmış şeklin çerçevesinin y-koordinatı, nokta cinsinden. |
| width | **float** | Klonlanmış şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Klonlanmış şeklin çerçevesinin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metod

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Yeni şekil *sourceShape*'ın genişliğini ve yüksekliğini korur.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanmış şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |
| x | **float** | Klonlanmış şeklin çerçevesinin x-koordinatı, nokta cinsinden. |
| y | **float** | Klonlanmış şeklin çerçevesinin y-koordinatı, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metod

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Klonlanmış şekil, orijinalin konum ve boyutunu korur.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Klonlanmış şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)