---
title: InsertZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Zoom çerçevesi oluşturur ve belirtilen dizindeki şekil koleksiyonuna ekler.
type: docs
weight: 118
url: /tr/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metodu

Yeni bir Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Zoom çerçevesinin ekleneceği sıfırdan başlayan dizin. |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından referans verilen [ISlide](../../islide/). |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir koleksiyonun belirtilen dizinine bir Zoom nesnesi oluşturup eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metodu

Önceden tanımlı bir görüntü ile yeni bir Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Zoom çerçevesinin ekleneceği sıfırdan başlayan dizin. |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından referans verilen [ISlide](../../islide/). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Referans verilen slayt [IPPImage](../../ippimage/) için görüntü. |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir koleksiyonun belirtilen dizinine bir Zoom nesnesi oluşturup eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IZoomFrame](../../izoomframe/)
* Sınıf [ISlide](../../islide/)
* Sınıf [ShapeCollection](../)
* Sınıf [IPPImage](../../ippimage/)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)