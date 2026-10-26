---
title: set_DefaultTextLanguage()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "प्रस्तुति पाठ के लिए डिफ़ॉल्ट भाषा सेट करता है। लिखें System::String."
type: docs
weight: 326
url: /hi/aspose.slides/loadoptions/set_defaulttextlanguage/
---
## LoadOptions::set_DefaultTextLanguage(System::String) विधि

प्रस्तुति पाठ के लिए डिफ़ॉल्ट भाषा सेट करता है। लिखें [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultTextLanguage(System::String value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
// नया आयताकार आकार टेक्स्ट के साथ जोड़ें
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
// पहले भाग की भाषा जाँचें
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)