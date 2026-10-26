---
title: get_DrawingGuides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 170
url: /hi/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() मेथड

मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// स्लाइड के केंद्र के दाईं ओर नई लंबवत ड्रॉइंग गाइड जोड़ना
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [MasterSlide](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)