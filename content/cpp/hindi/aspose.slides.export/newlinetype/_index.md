---
title: NewLineType
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: उत्पन्न दस्तावेज़ में उपयोग की जाने वाली नई पंक्ति का प्रकार।
type: docs
weight: 963
url: /hi/aspose.slides.export/newlinetype/
---
## NewLineType enum

उत्पन्न दस्तावेज़ में उपयोग की जाने वाली नई पंक्ति का प्रकार।

```cpp
enum class NewLineType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS नई पंक्ति - \r\n |
| Unix | 1 | Unix & Mac OS X नई पंक्ति - \n |
| Mac | 2 | Mac (OS 9) नई पंक्ति - \r |

## टिप्पणी

उदाहरण
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## संदर्भ

* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)