---
title: Flavor
second_title: Aspose.Slides für C++ API-Referenz
description: Alle Markdown-Spezifikationen, die im Programm verwendet werden.
type: docs
weight: 924
url: /de/aspose.slides.export/flavor/
---
## Flavor-Enum

Alle Markdown-Spezifikationen, die im Programm verwendet werden.

```cpp
enum class Flavor
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Github | 0 | Github-Variante. |
| Gruber | 1 | Gruber-Variante. |
| MultiMarkdown | 2 | Multi-Markdown-Variante. |
| CommonMark | 3 | Common-Mark-Variante. |
| MarkdownExtra | 4 | Markdown-Extra-Variante. |
| Pandoc | 5 | Pandoc-Variante. |
| Kramdown | 6 | Kramdown-Variante. |
| Markua | 7 | Markua-Variante. |
| Maruku | 8 | Maruku-Variante. |
| Markdown2 | 9 | Markdown2-Variante. |
| Remarkable | 10 | Remarkable-Variante |
| Showdown | 11 | Showdown-Variante. |
| Ghost | 12 | Ghost-Variante. |
| GitLab | 13 | Gitlab-Variante. |
| Haroopad | 14 | Haroopad-Variante. |
| IaWriter | 15 | IAWriter-Variante. |
| Redcarpet | 16 | Redcarpet-Variante. |
| ScholarlyMarkdown | 17 | Scholarly-Markdown-Variante. |
| Taiga | 18 | Taiga-Variante. |
| Trello | 19 | Trello-Variante. |
| S9ETextFormatter | 20 | S9E-Text-Formatter-Variante. |
| XWiki | 21 | XWiki-Variante. |
| StackOverflow | 22 | Stack-Overflow-Variante. |
| Default | 23 | Default-Markdown-Variante. |

## Anmerkungen

Beispiel: 
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

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)