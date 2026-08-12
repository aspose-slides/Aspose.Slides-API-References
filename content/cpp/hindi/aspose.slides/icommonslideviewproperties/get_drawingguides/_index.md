---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 53
url: /hi/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() विधि

ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## टिप्पणियाँ

निम्नलिखित नमूना कोड दिखाता है कि एक PowerPoint प्रस्तुति में नए ड्राइंग गाइड्स कैसे जोड़े जाएँ। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// स्लाइड के केंद्र के दाएँ ओर नई लंबवत ड्राइंग गाइड जोड़ना
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// स्लाइड के केंद्र के नीचे नई क्षैतिज ड्राइंग गाइड जोड़ना
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [ICommonSlideViewProperties](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)