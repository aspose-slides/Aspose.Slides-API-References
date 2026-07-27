---
title: MarkdownExportType
second_title: Referência da API Aspose.Slides for C++
description: Tipo de renderização do documento.
type: docs
weight: 950
url: /pt/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

Tipo de renderização do documento.

```cpp
enum class MarkdownExportType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Sequential | 0 | Renderiza todos os itens separadamente. Um por um. |
| TextOnly | 1 | Renderiza apenas o texto. |
| Visual | 2 | Renderiza todos os itens, itens que estão agrupados - renderiza juntos. |

## Observações

Exemplo:
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

## Ver também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)