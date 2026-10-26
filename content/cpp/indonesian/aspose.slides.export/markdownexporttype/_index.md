---
title: MarkdownExportType
second_title: Referensi API Aspose.Slides untuk C++
description: Tipe dokumen yang dirender.
type: docs
weight: 950
url: /id/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Tipe dokumen yang dirender.

```cpp
enum class MarkdownExportType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Sequential | 0 | Render semua item secara terpisah. Satu per satu. |
| TextOnly | 1 | Render hanya teks. |
| Visual | 2 | Render semua item, item yang dikelompokkan - render bersama. |

## Catatan


Contoh: 
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

## Lihat Juga

* Ruang Nama [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)