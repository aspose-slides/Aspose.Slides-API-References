---
title: Flavor
second_title: Riferimento API di Aspose.Slides per C++
description: Tutte le specifiche markdown utilizzate nel programma.
type: docs
weight: 924
url: /it/aspose.slides.export/flavor/
---
## Flavor enum


All markdown specifications used in program.

```cpp
enum class Flavor
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Github | 0 | Github variante. |
| Gruber | 1 | Gruber variante. |
| MultiMarkdown | 2 | Multi markdown variante. |
| CommonMark | 3 | Common mark variante. |
| MarkdownExtra | 4 | Markdown extra variante. |
| Pandoc | 5 | Pandoc variante. |
| Kramdown | 6 | Kramdown variante. |
| Markua | 7 | Markua variante. |
| Maruku | 8 | Maruku variante. |
| Markdown2 | 9 | Markdown2 variante. |
| Remarkable | 10 | Remarkable variante |
| Showdown | 11 | Showdown variante. |
| Ghost | 12 | Ghost variante. |
| GitLab | 13 | Gitlab variante. |
| Haroopad | 14 | Haroopad variante. |
| IaWriter | 15 | IAWriter variante. |
| Redcarpet | 16 | Redcarpet variante. |
| ScholarlyMarkdown | 17 | Scholarly markdown variante. |
| Taiga | 18 | Taiga variante. |
| Trello | 19 | Trello variante. |
| S9ETextFormatter | 20 | S9E text formatter variante. |
| XWiki | 21 | XWiki variante. |
| StackOverflow | 22 | Stack overflow variante. |
| Default | 23 | Default markdown variante. |

## Osservazioni


Esempio: 
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

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)