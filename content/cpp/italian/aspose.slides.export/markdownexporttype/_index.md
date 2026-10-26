---
title: MarkdownExportType
second_title: Aspose.Slides per C++ Riferimento API
description: Tipo di rendering del documento.
type: docs
weight: 950
url: /it/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Tipo di rendering del documento.

```cpp
enum class MarkdownExportType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Sequential | 0 | Renderizza tutti gli elementi separatamente. Uno alla volta. |
| TextOnly | 1 | Renderizza solo il testo. |
| Visual | 2 | Renderizza tutti gli elementi, gli elementi raggruppati - renderizza insieme. |

## Osservazioni


Esempio: 
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

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)