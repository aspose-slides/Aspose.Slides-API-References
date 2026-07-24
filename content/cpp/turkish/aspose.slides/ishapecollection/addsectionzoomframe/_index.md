---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 118
url: /tr/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) yöntem

Yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, nokta biriminde. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) referans verilen [Section](../../section/) Zoom çerçevesi; bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar

Bu örnek, bir [Section](../../section/) Zoom nesnesinin bir koleksiyonun sonuna eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğu varsayılır):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) yöntemi

Önceden tanımlı bir görüntü ile yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, nokta biriminde. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) referans verilen [Section](../../section/) Zoom çerçevesi; bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) [Section](../../section/) Zoom çerçevesi içinde görüntülenecek. |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar

Bu örnek, bir [Section](../../section/) Zoom nesnesinin bir koleksiyonun sonuna eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğu varsayılır):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)