---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ड्रॉइंग गाइड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 53
url: /hi/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() विधि


ड्रॉइंग गाइड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## टिप्पणियाँ


निम्नलिखित नमूना कोड यह दर्शाता है कि कैसे नई ड्रॉइंग गाइड्स को एक PowerPoint प्रस्तुति में जोड़ा जा सकता है। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// स्लाइड के केंद्र के दाएँ हिस्से में नया लंबवत ड्रॉइंग गाइड जोड़ रहा है
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// स्लाइड के केंद्र के नीचे नया क्षैतिज ड्रॉइंग गाइड जोड़ रहा है
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [CommonSlideViewProperties](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)