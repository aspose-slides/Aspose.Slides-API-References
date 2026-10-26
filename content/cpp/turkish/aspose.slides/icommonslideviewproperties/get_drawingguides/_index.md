---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Referansı
description: Çizim kılavuzlarının koleksiyonunu döndürür. Salt okunur IDrawingGuidesCollection
type: docs
weight: 53
url: /tr/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() method

Çizim kılavuzlarının koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Açıklamalar

Aşağıdaki örnek kod, bir PowerPoint sunumunda yeni çizim kılavuzlarının nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Slayt merkezinin sağ tarafına yeni dikey çizim kılavuzu ekleniyor
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Slayt merkezinin altına yeni yatay çizim kılavuzu ekleniyor
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [ICommonSlideViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)