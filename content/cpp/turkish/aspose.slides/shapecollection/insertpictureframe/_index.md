---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve bunu belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 456
url: /tr/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metod


Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve bunu belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Resim çerçevesinin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) içinde bulunan şekil tipini belirtir, ancak tüm çizgi türleri hariç: <br>[ShapeType::Line](../../shapetype/),<br>[ShapeType::StraightConnector1](../../shapetype/),<br>[ShapeType::BentConnector2](../../shapetype/),<br>[ShapeType::BentConnector3](../../shapetype/),<br>[ShapeType::BentConnector4](../../shapetype/),<br>[ShapeType::BentConnector5](../../shapetype/),<br>[ShapeType::CurvedConnector2](../../shapetype/),<br>[ShapeType::CurvedConnector3](../../shapetype/),<br>[ShapeType::CurvedConnector4](../../shapetype/),<br>[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Resim çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Resim çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Resim çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Resim çerçevesinin yüksekliği, puan cinsinden. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Resim çerçevesinde gösterilecek [IPPImage](../../ippimage/). |

### Dönüş Değeri

Yeni oluşturulan [IPictureFrame](../../ipictureframe/).

## İlgili

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPictureFrame](../../ipictureframe/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)