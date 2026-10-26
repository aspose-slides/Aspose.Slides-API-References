---
title: AddPictureFrame()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 443
url: /tr/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) yöntemi


Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) içinde bulunan şekil tipini belirtir, tüm çizgi türleri hariç: |
|  |  | [ShapeType::Line](../../shapetype/), |
|  |  | [ShapeType::StraightConnector1](../../shapetype/), |
|  |  | [ShapeType::BentConnector2](../../shapetype/), |
|  |  | [ShapeType::BentConnector3](../../shapetype/), |
|  |  | [ShapeType::BentConnector4](../../shapetype/), |
|  |  | [ShapeType::BentConnector5](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector2](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector3](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector4](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Resim çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Resim çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Resim çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Resim çerçevesinin yüksekliği, puan cinsinden. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Resim çerçevesinde görüntülenecek [IPPImage](../../ippimage/). |

### Dönüş Değeri

Yeni oluşturulan [IPictureFrame](../../ipictureframe/).

## Ayrıca Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPictureFrame](../../ipictureframe/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [ShapeCollection](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)