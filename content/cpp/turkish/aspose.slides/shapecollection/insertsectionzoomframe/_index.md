---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Section Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.
type: docs
weight: 144
url: /tr/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) yöntemi

Belirtilen indeks'te şekil koleksiyonuna yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve ekler.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Sıfır tabanlı indeks, [Section](../../section/) Zoom çerçevesinin ekleneceği konum. |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### Dönen Değer

[ISectionZoomFrame](../../isectionzoomframe/) yeni oluşturuldu.

## Açıklamalar

Bu örnek, bir koleksiyonun belirtilen indeksine bir [Section](../../section/) Zoom nesnesi oluşturulup eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayın): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) yöntemi

Belirtilen indeks'te şekil koleksiyonuna önceden tanımlı bir resim içeren yeni bir [Section](../../section/) Zoom çerçevesi oluşturur ve ekler.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Sıfır tabanlı indeks, [Section](../../section/) Zoom çerçevesinin ekleneceği konum. |
| x | **float** | Yeni [Section](../../section/) Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni [Section](../../section/) Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni [Section](../../section/) Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni [Section](../../section/) Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom çerçevesi tarafından referans verilen [ISection](../../isection/); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom çerçevesi içinde gösterilecek resim. |

### Dönen Değer

[ISectionZoomFrame](../../isectionzoomframe/) yeni oluşturuldu.

## Açıklamalar

Bu örnek, bir koleksiyonun belirtilen indeksine bir [Section](../../section/) Zoom nesnesi oluşturulup eklenmesini gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayın): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISectionZoomFrame](../../isectionzoomframe/)
* Sınıf [ISection](../../isection/)
* Sınıf [ShapeCollection](../)
* Sınıf [IPPImage](../../ippimage/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)