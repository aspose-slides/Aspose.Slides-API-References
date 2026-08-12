---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API संदर्भ
description: मास्टर नोट्स स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। Read-only IDrawingGuidesCollection
type: docs
weight: 27
url: /hi/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() method


मास्टर नोट्स स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// स्लाइड के केंद्र के नीचे नई क्षैतिज ड्रॉइंग गाइड जोड़ना
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [IMasterNotesSlide](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)