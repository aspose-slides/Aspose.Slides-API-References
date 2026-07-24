---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Referansı
description: Ana slayt için çizim kılavuzlarından oluşan bir koleksiyon döndürür. Salt okunur IDrawingGuidesCollection
type: docs
weight: 105
url: /tr/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() metodu


Ana slayt için çizim kılavuzlarından oluşan bir koleksiyon döndürür. Salt okunur [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Slayt merkezinin sağ tarafına yeni dikey çizim kılavuzu ekleniyor
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Sınıf [IMasterSlide](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)