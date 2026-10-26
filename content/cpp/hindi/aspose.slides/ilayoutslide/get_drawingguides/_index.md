---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 79
url: /hi/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() विधि

लेआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// स्लाइड केंद्र के बाएं हिस्से में नया लंबवत ड्रॉइंग गाइड जोड़ रहा है
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## और देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [ILayoutSlide](../)
* नेमस्पेस [Aspose::Slides](../../)
* लैब्रेरी [Aspose.Slides](../../../)