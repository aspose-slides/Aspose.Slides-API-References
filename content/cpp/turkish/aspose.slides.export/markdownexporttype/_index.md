---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API Referansı
description: Belgenin işlenme türü.
type: docs
weight: 950
url: /tr/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Belgeyi işleme türü.

```cpp
enum class MarkdownExportType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Sequential | 0 | Tüm ögeleri ayrı ayrı işleyin. Tek tek. |
| TextOnly | 1 | Yalnızca metni işleyin. |
| Visual | 2 | Tüm ögeleri, gruplanmış olanları birlikte işleyin. |

## Açıklamalar


Örnek: 
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

## İlgili

* İsim Uzayı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)