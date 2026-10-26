---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 313
url: /tr/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metod

Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/)'ı. |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metod

Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/)'ı. |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |
| createFromTemplate | **bool** | Yeni şekle varsayılan şablon stilini (basit stil, ortalanmış metin ve boş olmayan ad) uygulamak için true; tüm özellikleri varsayılan değerlerine ayarlayarak şekli oluşturmak için false. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## Ayrıca Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)