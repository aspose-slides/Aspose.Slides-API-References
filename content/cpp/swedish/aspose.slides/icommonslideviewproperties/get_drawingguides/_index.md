---
title: get_DrawingGuides()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av ritguiderna. Endast läsning IDrawingGuidesCollection
type: docs
weight: 53
url: /sv/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metod

Returnerar samlingen av ritguiderna. Endast läsning [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Anmärkningar

Följande exempel kod visar hur man lägger till de nya ritguiderna i en PowerPoint-presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Lägger till den nya vertikala ritguiden till höger om bildens centrum
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Lägger till den nya horisontella ritguiden under bildens centrum
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klass [ICommonSlideViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)