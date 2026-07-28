---
title: MarkdownExportType
second_title: Dokumentacja API Aspose.Slides dla C++
description: Typ renderowania dokumentu.
type: docs
weight: 950
url: /pl/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

Typ renderowania dokumentu.

```cpp
enum class MarkdownExportType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Sequential | 0 | Renderuj wszystkie elementy osobno. Jeden po drugim. |
| TextOnly | 1 | Renderuj tylko tekst. |
| Visual | 2 | Renderuj wszystkie elementy, elementy zgrupowane - renderuj razem. |

## Uwagi

Przykład:
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

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)