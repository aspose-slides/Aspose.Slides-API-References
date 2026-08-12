---
title: MarkdownExportType
second_title: Aspose.Slides C++ के लिये API संदर्भ
description: दस्तावेज़ को रेंडर करने का प्रकार।
type: docs
weight: 950
url: /hi/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

दस्तावेज़ को रेंडर करने का प्रकार।

```cpp
enum class MarkdownExportType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Sequential | 0 | सभी आइटम को अलग-अलग रेंडर करें। एक-एक करके। |
| TextOnly | 1 | केवल टेक्स्ट रेंडर करें। |
| Visual | 2 | सभी आइटम रेंडर करें, समूहित आइटम - साथ में रेंडर करें। |

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## देखें

* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)