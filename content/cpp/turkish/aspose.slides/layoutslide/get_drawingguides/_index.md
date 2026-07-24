---
title: get_DrawingGuides()
second_title: Aspose.Slides için C++ API Referansı
description: Düzen slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur IDrawingGuidesCollection
type: docs
weight: 118
url: /tr/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() metodu


Düzen slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Slayt merkezinin sol tarafına yeni dikey çizim kılavuzu ekleniyor
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Sınıf [LayoutSlide](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)