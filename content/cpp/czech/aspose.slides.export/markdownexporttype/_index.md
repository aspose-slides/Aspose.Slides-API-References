---
title: MarkdownExportType
second_title: Aspose.Slides pro C++ API Reference
description: Typ vykreslování dokumentu.
type: docs
weight: 950
url: /cs/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enumerace

Typ vykreslování dokumentu.

```cpp
enum class MarkdownExportType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Sequential | 0 | Vykreslit všechny položky samostatně. Jednu po druhé. |
| TextOnly | 1 | Vykreslit pouze text. |
| Visual | 2 | Vykreslit všechny položky, položky, které jsou seskupeny - vykreslit společně. |

## Poznámky

Příklad:
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

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)