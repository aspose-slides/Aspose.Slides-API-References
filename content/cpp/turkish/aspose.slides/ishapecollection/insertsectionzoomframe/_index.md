---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Section Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 131
url: /tr/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) yöntemi

Yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni [Section](../../section/) Zoom çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar

Bu örnek, bir [Section](../../section/) Zoom nesnesinin bir koleksiyonun belirtilen dizinine oluşturulmasını ve eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayalım): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) yöntemi

Önceden tanımlı bir görüntüye sahip yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni [Section](../../section/) Zoom çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom çerçevesi içinde gösterilecek görüntü. |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar

Bu örnek, bir [Section](../../section/) Zoom nesnesinin bir koleksiyonun belirtilen dizinine oluşturulmasını ve eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayalım): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## İlgili

* Tanımlama [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISectionZoomFrame](../../isectionzoomframe/)
* Sınıf [ISection](../../isection/)
* Sınıf [IShapeCollection](../)
* Sınıf [IPPImage](../../ippimage/)
* Adalanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)