---
title: Flavor
second_title: Referência da API Aspose.Slides para C++
description: Todas as especificações de markdown usadas no programa.
type: docs
weight: 924
url: /pt/aspose.slides.export/flavor/
---
## Flavor enum

Todas as especificações de markdown usadas no programa.

```cpp
enum class Flavor
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Github | 0 | Sabor Github. |
| Gruber | 1 | Sabor Gruber. |
| MultiMarkdown | 2 | Sabor Multi markdown. |
| CommonMark | 3 | Sabor Common mark. |
| MarkdownExtra | 4 | Sabor Markdown extra. |
| Pandoc | 5 | Sabor Pandoc. |
| Kramdown | 6 | Sabor Kramdown. |
| Markua | 7 | Sabor Markua. |
| Maruku | 8 | Sabor Maruku. |
| Markdown2 | 9 | Sabor Markdown2. |
| Remarkable | 10 | Sabor Remarkable |
| Showdown | 11 | Sabor Showdown. |
| Ghost | 12 | Sabor Ghost. |
| GitLab | 13 | Sabor Gitlab. |
| Haroopad | 14 | Sabor Haroopad. |
| IaWriter | 15 | Sabor IAWriter. |
| Redcarpet | 16 | Sabor Redcarpet. |
| ScholarlyMarkdown | 17 | Sabor Scholarly markdown. |
| Taiga | 18 | Sabor Taiga. |
| Trello | 19 | Sabor Trello. |
| S9ETextFormatter | 20 | Sabor S9E formatador de texto. |
| XWiki | 21 | Sabor XWiki. |
| StackOverflow | 22 | Sabor Stack overflow. |
| Default | 23 | Sabor padrão markdown. |

## Observações

Exemplo: 
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

## Veja também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)