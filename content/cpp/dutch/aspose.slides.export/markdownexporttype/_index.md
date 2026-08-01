---
title: MarkdownExportType
second_title: Aspose.Slides voor C++ API-referentie
description: Type van documentweergave.
type: docs
weight: 950
url: /nl/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Type van documentweergave.

```cpp
enum class MarkdownExportType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Sequential | 0 | Render alle items afzonderlijk. Eén voor één. |
| TextOnly | 1 | Render alleen tekst. |
| Visual | 2 | Render alle items, items die gegroepeerd zijn - render samen. |

## Opmerkingen


Voorbeeld: 
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

## Zie ook

* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)