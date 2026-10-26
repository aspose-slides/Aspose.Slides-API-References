---
title: AddClone()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 547
url: /tr/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak şekil. |
| x | **float** | Yeni şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil *sourceShape* öğesinin genişlik ve yüksekliğini korur.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak şekil. |
| x | **float** | Yeni şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni şeklin çerçevesinin y koordinatı, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Klonlanan şekil, orijinalin konum ve boyutunu korur.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [ShapeCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)