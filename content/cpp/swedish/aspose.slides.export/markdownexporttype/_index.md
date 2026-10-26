---
title: MarkdownExportType
second_title: Aspose.Slides för C++ API-referens
description: Typ av renderingsdokument.
type: docs
weight: 950
url: /sv/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Typ av renderingsdokument.

```cpp
enum class MarkdownExportType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Sequential | 0 | Rendera alla objekt separat. Ett i taget. |
| TextOnly | 1 | Rendera endast text. |
| Visual | 2 | Rendera alla objekt, objekt som är grupperade - rendera tillsammans. |

## Anmärkningar


Exempel:
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

## Se också

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)