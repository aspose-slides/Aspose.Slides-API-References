---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API Referencia
description: A dokumentum renderelésének típusa.
type: docs
weight: 950
url: /hu/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

A dokumentum renderelésének típusa.

```cpp
enum class MarkdownExportType
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Sequential | 0 | Az összes elemet külön-külön rendereli. Egyesével. |
| TextOnly | 1 | Csak a szöveget rendereli. |
| Visual | 2 | Az összes elemet rendereli, a csoportosított elemeket együtt rendereli. |

## Megjegyzés


Példa: 
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

## Lásd még

* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)