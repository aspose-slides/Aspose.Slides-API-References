---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir otomatik şekil oluşturur ve belirtilen dizindeki şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular.
type: docs
weight: 339
url: /tr/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method


Yeni bir otomatik şekil oluşturur ve belirtilen konumdaki şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni otomatik şeklin ekleneceği sıfır tabanlı dizin. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method


Yeni bir otomatik şekil oluşturur ve belirtilen konumdaki şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stiliniyle başlatır.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Otomatik şeklin ekleneceği sıfır tabanlı dizin. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | **bool** | Varsayılan şablon stilini uygulamak için True (boş olmayan bir isim, basit stil ve ortalanmış metin içerir); tüm özellikleri varsayılanlarına ayarlanmış şekilde şekli oluşturmak için false. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## İlgili

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)