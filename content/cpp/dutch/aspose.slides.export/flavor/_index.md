---
title: Flavor
second_title: Aspose.Slides voor C++ API-referentie
description: Alle markdownspecificaties die in het programma worden gebruikt.
type: docs
weight: 924
url: /nl/aspose.slides.export/flavor/
---
## Flavor enum

Alle markdown-specificaties die in het programma worden gebruikt.

```cpp
enum class Flavor
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Github | 0 | Github variant. |
| Gruber | 1 | Gruber variant. |
| MultiMarkdown | 2 | Multi markdown variant. |
| CommonMark | 3 | Common mark variant. |
| MarkdownExtra | 4 | Markdown extra variant. |
| Pandoc | 5 | Pandoc variant. |
| Kramdown | 6 | Kramdown variant. |
| Markua | 7 | Markua variant. |
| Maruku | 8 | Maruku variant. |
| Markdown2 | 9 | Markdown2 variant. |
| Remarkable | 10 | Remarkable variant |
| Showdown | 11 | Showdown variant. |
| Ghost | 12 | Ghost variant. |
| GitLab | 13 | Gitlab variant. |
| Haroopad | 14 | Haroopad variant. |
| IaWriter | 15 | IAWriter variant. |
| Redcarpet | 16 | Redcarpet variant. |
| ScholarlyMarkdown | 17 | Scholarly markdown variant. |
| Taiga | 18 | Taiga variant. |
| Trello | 19 | Trello variant. |
| S9ETextFormatter | 20 | S9E text formatter variant. |
| XWiki | 21 | XWiki variant. |
| StackOverflow | 22 | Stack overflow variant. |
| Default | 23 | Standaard markdown variant. |

## Opmerkingen

Voorbeeld: 
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

## Zie ook

* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)