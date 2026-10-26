---
title: Flavor
second_title: Referencia de API de Aspose.Slides for C++
description: Todas las especificaciones markdown usadas en el programa.
type: docs
weight: 924
url: /es/aspose.slides.export/flavor/
---
## enum Flavor

Todas las especificaciones markdown usadas en el programa.

```cpp
enum class Flavor
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Github | 0 | Github sabor. |
| Gruber | 1 | Gruber sabor. |
| MultiMarkdown | 2 | Multi markdown sabor. |
| CommonMark | 3 | Common mark sabor. |
| MarkdownExtra | 4 | Markdown extra sabor. |
| Pandoc | 5 | Pandoc sabor. |
| Kramdown | 6 | Kramdown sabor. |
| Markua | 7 | Markua sabor. |
| Maruku | 8 | Maruku sabor. |
| Markdown2 | 9 | Markdown2 sabor. |
| Remarkable | 10 | Remarkable sabor |
| Showdown | 11 | Showdown sabor. |
| Ghost | 12 | Ghost sabor. |
| GitLab | 13 | Gitlab sabor. |
| Haroopad | 14 | Haroopad sabor. |
| IaWriter | 15 | IAWriter sabor. |
| Redcarpet | 16 | Redcarpet sabor. |
| ScholarlyMarkdown | 17 | Scholarly markdown sabor. |
| Taiga | 18 | Taiga sabor. |
| Trello | 19 | Trello sabor. |
| S9ETextFormatter | 20 | S9E text formatter sabor. |
| XWiki | 21 | XWiki sabor. |
| StackOverflow | 22 | Stack overflow sabor. |
| Default | 23 | Default markdown sabor. |

## Observaciones

Ejemplo: 
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

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)