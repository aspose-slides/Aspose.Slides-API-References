---
title: get_DrawingGuides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मास्टर हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य IDrawingGuidesCollection
type: docs
weight: 14
url: /hi/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() विधि


मास्टर हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IDrawingGuidesCollection](../../idrawingguidescollection/)
* क्लास [IMasterHandoutSlide](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)