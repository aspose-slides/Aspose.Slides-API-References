---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 417
url: /tr/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metodu


Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Resim çerçevesinin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | Şekil türünü [ShapeType](../../shapetype/) içinde belirtir, tüm çizgi türleri hariç:  

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Resim çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Resim çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Resim çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Resim çerçevesinin yüksekliği, nokta cinsinden. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Resim çerçevesinde görüntülenecek [IPPImage](../../ippimage/). |

### Dönüş Değeri

Yeni oluşturulan [IPictureFrame](../../ipictureframe/).

## Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPictureFrame](../../ipictureframe/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [IShapeCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)