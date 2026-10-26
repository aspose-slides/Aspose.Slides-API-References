---
title: Flavor
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रोग्राम में उपयोग की गई सभी मार्कडाउन विनिर्देश।
type: docs
weight: 924
url: /hi/aspose.slides.export/flavor/
---
## फ़्लेवर एन्नुम

All markdown specifications used in program.

```cpp
enum class Flavor
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Github | 0 | Github फ़्लेवर। |
| Gruber | 1 | Gruber फ़्लेवर। |
| MultiMarkdown | 2 | Multi मार्कडाउन फ़्लेवर। |
| CommonMark | 3 | Common मार्क फ़्लेवर। |
| MarkdownExtra | 4 | Markdown एक्स्ट्रा फ़्लेवर। |
| Pandoc | 5 | Pandoc फ़्लेवर। |
| Kramdown | 6 | Kramdown फ़्लेवर। |
| Markua | 7 | Markua फ़्लेवर। |
| Maruku | 8 | Maruku फ़्लेवर। |
| Markdown2 | 9 | Markdown2 फ़्लेवर। |
| Remarkable | 10 | Remarkable फ़्लेवर |
| Showdown | 11 | Showdown फ़्लेवर। |
| Ghost | 12 | Ghost फ़्लेवर। |
| GitLab | 13 | Gitlab फ़्लेवर। |
| Haroopad | 14 | Haroopad फ़्लेवर। |
| IaWriter | 15 | IAWriter फ़्लेवर। |
| Redcarpet | 16 | Redcarpet फ़्लेवर। |
| ScholarlyMarkdown | 17 | Scholarly मार्कडाउन फ़्लेवर। |
| Taiga | 18 | Taiga फ़्लेवर। |
| Trello | 19 | Trello फ़्लेवर। |
| S9ETextFormatter | 20 | S9E टेक्स्ट फ़ॉर्मैटर फ़्लेवर। |
| XWiki | 21 | XWiki फ़्लेवर। |
| StackOverflow | 22 | Stack ओवरफ़्लो फ़्लेवर। |
| Default | 23 | Default मार्कडाउन फ़्लेवर। |

## टिप्पणियाँ

Example: 
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

## संबंधित देखें

* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)