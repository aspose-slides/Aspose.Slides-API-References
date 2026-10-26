---
title: AddZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 92
url: /tr/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) yöntem

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından referans verilen [ISlide](../../islide/); bu sunuma ait olmalıdır. |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir Zoom nesnesini bir koleksiyonun sonuna eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) yöntemi

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom çerçevesi tarafından referans verilen [ISlide](../../islide/); bu sunuma ait olmalıdır. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Referans verilen slayt [IPPImage](../../ippimage/) için resim. |

### Dönüş Değeri

Yeni oluşturulan [IZoomFrame](../../izoomframe/).

## Açıklamalar

Bu örnek, bir Zoom nesnesini bir koleksiyonun sonuna eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki slayt olduğunu varsayın): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IZoomFrame](../../izoomframe/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IShapeCollection](../)
* Sınıf [IPPImage](../../ippimage/)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)