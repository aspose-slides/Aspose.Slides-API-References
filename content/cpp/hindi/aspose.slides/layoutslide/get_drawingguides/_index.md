---
title: get_DrawingGuides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लेआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 118
url: /hi/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() मेथड

लेआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// स्लाइड केंद्र के बाएँ तरफ नया ऊर्ध्वाधर ड्राइंग गाइड जोड़ रहा है
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## अन्य देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* कक्षा [IDrawingGuidesCollection](../../idrawingguidescollection/)
* कक्षा [LayoutSlide](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)