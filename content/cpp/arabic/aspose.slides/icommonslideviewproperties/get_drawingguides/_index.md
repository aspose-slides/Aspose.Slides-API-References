---
title: get_DrawingGuides()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يَرجِع مجموعة إرشادات الرسم. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 53
url: /ar/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() الطريقة


يرجع مجموعة إرشادات الرسم. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## ملاحظات


يظهر الشيفرة النموذجية التالية كيفية إضافة إرشادات الرسم الجديدة في عرض PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [ICommonSlideViewProperties](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)