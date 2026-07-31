---
title: Flavor
second_title: Referensi API Aspose.Slides untuk C++
description: Semua spesifikasi markdown yang digunakan dalam program.
type: docs
weight: 924
url: /id/aspose.slides.export/flavor/
---
## Enum Flavor

Semua spesifikasi markdown yang digunakan dalam program.

```cpp
enum class Flavor
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Github | 0 | Varian Github. |
| Gruber | 1 | Varian Gruber. |
| MultiMarkdown | 2 | Varian MultiMarkdown. |
| CommonMark | 3 | Varian CommonMark. |
| MarkdownExtra | 4 | Varian Markdown extra. |
| Pandoc | 5 | Varian Pandoc. |
| Kramdown | 6 | Varian Kramdown. |
| Markua | 7 | Varian Markua. |
| Maruku | 8 | Varian Maruku. |
| Markdown2 | 9 | Varian Markdown2. |
| Remarkable | 10 | Varian Remarkable. |
| Showdown | 11 | Varian Showdown. |
| Ghost | 12 | Varian Ghost. |
| GitLab | 13 | Varian Gitlab. |
| Haroopad | 14 | Varian Haroopad. |
| IaWriter | 15 | Varian IAWriter. |
| Redcarpet | 16 | Varian Redcarpet. |
| ScholarlyMarkdown | 17 | Varian Scholarly markdown. |
| Taiga | 18 | Varian Taiga. |
| Trello | 19 | Varian Trello. |
| S9ETextFormatter | 20 | Varian S9E text formatter. |
| XWiki | 21 | Varian XWiki. |
| StackOverflow | 22 | Varian Stack overflow. |
| Default | 23 | Varian markdown default. |

## Keterangan

Contoh:
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

## Lihat Juga

* Ruang nama [Aspose::Slides::Export](../)
* Pustaka [Aspose.Slides](../../)