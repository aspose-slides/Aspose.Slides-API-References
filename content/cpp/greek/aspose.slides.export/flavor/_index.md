---
title: Flavor
second_title: Aspose.Slides για C++ API αναφορά
description: Όλες οι προδιαγραφές markdown που χρησιμοποιούνται στο πρόγραμμα.
type: docs
weight: 924
url: /el/aspose.slides.export/flavor/
---
## Enum Flavor


All markdown specifications used in program.

```cpp
enum class Flavor
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Github | 0 | Μορφή Github. |
| Gruber | 1 | Μορφή Gruber. |
| MultiMarkdown | 2 | Μορφή Multi markdown. |
| CommonMark | 3 | Μορφή Common mark. |
| MarkdownExtra | 4 | Μορφή Markdown extra. |
| Pandoc | 5 | Μορφή Pandoc. |
| Kramdown | 6 | Μορφή Kramdown. |
| Markua | 7 | Μορφή Markua. |
| Maruku | 8 | Μορφή Maruku. |
| Markdown2 | 9 | Μορφή Markdown2. |
| Remarkable | 10 | Μορφή Remarkable |
| Showdown | 11 | Μορφή Showdown. |
| Ghost | 12 | Μορφή Ghost. |
| GitLab | 13 | Μορφή Gitlab. |
| Haroopad | 14 | Μορφή Haroopad. |
| IaWriter | 15 | Μορφή IAWriter. |
| Redcarpet | 16 | Μορφή Redcarpet. |
| ScholarlyMarkdown | 17 | Μορφή Scholarly markdown. |
| Taiga | 18 | Μορφή Taiga. |
| Trello | 19 | Μορφή Trello. |
| S9ETextFormatter | 20 | Μορφή S9E text formatter. |
| XWiki | 21 | Μορφή XWiki. |
| StackOverflow | 22 | Μορφή Stack overflow. |
| Default | 23 | Μορφή Default markdown. |

## Σχόλια


Παράδειγμα: 
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

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)