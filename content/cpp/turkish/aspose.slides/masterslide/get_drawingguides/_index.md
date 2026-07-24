---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Referansı
description: Ana slayt için bir dizi çizim kılavuzu döndürür. Yalnızca okunur IDrawingGuidesCollection
type: docs
weight: 170
url: /tr/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() yöntemi

Ana slayt için bir dizi çizim kılavuzu döndürür. Yalnızca okunur [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Yeni dikey çizim kılavuzunu slayt merkezinin sağına ekleme
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Sınıf [MasterSlide](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)