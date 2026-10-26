---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 131
url: /tr/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metod


Yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar


Bu örnek, bir [Section](../../section/) Zoom nesnesini bir koleksiyonun sonuna eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayalım): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metod


Yeni bir [Section](../../section/) Zoom çerçevesi, önceden tanımlanmış bir görüntü ile oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom çerçevesi içinde gösterilecek [IPPImage](../../ippimage/). |

### Dönüş Değeri

Yeni oluşturulan [ISectionZoomFrame](../../isectionzoomframe/).

## Açıklamalar


Bu örnek, bir [Section](../../section/) Zoom nesnesini bir koleksiyonun sonuna eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayalım): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)