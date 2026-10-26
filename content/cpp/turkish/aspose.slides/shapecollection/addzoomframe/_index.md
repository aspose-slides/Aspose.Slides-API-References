---
title: AddZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 105
url: /tr/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından başvurulan [ISlide](../../islide/); bu sunuma ait olmalıdır. |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından başvurulan [ISlide](../../islide/); bu sunuma ait olmalıdır. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Başvurulan slayt [IPPImage](../../ippimage/) için görüntü. |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)