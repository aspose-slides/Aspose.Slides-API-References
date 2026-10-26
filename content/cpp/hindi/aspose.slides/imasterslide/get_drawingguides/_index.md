---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: मास्टर स्लाइड के लिए ड्रॉइंग गाइड का संग्रह लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 105
url: /hi/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() मेथड

मास्टर स्लाइड के लिए ड्रॉइंग गाइड का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
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

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [IMasterSlide](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)