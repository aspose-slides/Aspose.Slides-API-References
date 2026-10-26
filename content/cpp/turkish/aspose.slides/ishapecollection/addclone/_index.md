---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 495
url: /tr/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) yöntem

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak şekil. |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Klonlanan şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Klonlanan şeklin çerçevesinin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) yöntem

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, *sourceShape*'in genişlik ve yüksekliğini korur.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) yöntem

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Klonlanan şekil, orijinalin konum ve boyutunu korur.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Klonlanacak [IShape](../../ishape/). |

### Dönüş Değeri

Yeni oluşturulan [IShape](../../ishape/).

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)