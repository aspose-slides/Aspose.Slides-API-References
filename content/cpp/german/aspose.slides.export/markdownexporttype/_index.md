---
title: MarkdownExportType
second_title: Aspose.Slides für C++ API Referenz
description: Typ der Dokumentdarstellung.
type: docs
weight: 950
url: /de/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType Enum

Typ der Dokumentdarstellung.

```cpp
enum class MarkdownExportType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Sequential | 0 | Rendert alle Elemente einzeln. Eins nach dem anderen. |
| TextOnly | 1 | Rendert nur Text. |
| Visual | 2 | Rendert alle Elemente, gruppierte Elemente werden zusammen gerendert. |

## Hinweise

Beispiel:
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

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)