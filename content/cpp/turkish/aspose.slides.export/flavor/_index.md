---
title: Flavor
second_title: Aspose.Slides için C++ API Referansı
description: Programda kullanılan tüm markdown spesifikasyonları.
type: docs
weight: 924
url: /tr/aspose.slides.export/flavor/
---
## Flavor enum

Programda kullanılan tüm markdown özellikleri.

```cpp
enum class Flavor
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Github | 0 | Github lezzeti. |
| Gruber | 1 | Gruber lezzeti. |
| MultiMarkdown | 2 | Multi markdown lezzeti. |
| CommonMark | 3 | Common mark lezzeti. |
| MarkdownExtra | 4 | Markdown extra lezzeti. |
| Pandoc | 5 | Pandoc lezzeti. |
| Kramdown | 6 | Kramdown lezzeti. |
| Markua | 7 | Markua lezzeti. |
| Maruku | 8 | Maruku lezzeti. |
| Markdown2 | 9 | Markdown2 lezzeti. |
| Remarkable | 10 | Remarkable lezzeti |
| Showdown | 11 | Showdown lezzeti. |
| Ghost | 12 | Ghost lezzeti. |
| GitLab | 13 | Gitlab lezzeti. |
| Haroopad | 14 | Haroopad lezzeti. |
| IaWriter | 15 | IAWriter lezzeti. |
| Redcarpet | 16 | Redcarpet lezzeti. |
| ScholarlyMarkdown | 17 | Scholarly markdown lezzeti. |
| Taiga | 18 | Taiga lezzeti. |
| Trello | 19 | Trello lezzeti. |
| S9ETextFormatter | 20 | S9E text formatter lezzeti. |
| XWiki | 21 | XWiki lezzeti. |
| StackOverflow | 22 | Stack overflow lezzeti. |
| Default | 23 | Varsayılan markdown lezzeti. |

## Açıklamalar

Örnek: 
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

## Ayrıca bakınız

* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)