---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir otomatik şekil, varsayılan biçimlendirme ile oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 352
url: /tr/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

Yeni bir otomatik şekil oluşturur ve varsayılan biçimlendirme ile şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Eklemek için otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Return Value

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Eklemek için otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | **bool** | Yeni şekle varsayılan şablon stilini (basit stil, ortalanmış metin ve boş olmayan ad) uygulamak için true; tüm özellikleri varsayılan değerlerine ayarlayarak şekli oluşturmak için false. |

### Return Value

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## İlgili

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)