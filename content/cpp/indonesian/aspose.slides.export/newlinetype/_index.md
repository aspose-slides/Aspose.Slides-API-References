---
title: NewLineType
second_title: Referensi API Aspose.Slides untuk C++
description: Jenis baris baru yang akan digunakan dalam dokumen yang dihasilkan.
type: docs
weight: 963
url: /id/aspose.slides.export/newlinetype/
---
## NewLineType enum

Jenis baris baru yang akan digunakan dalam dokumen yang dihasilkan.

```cpp
enum class NewLineType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS baris baru - \r\n |
| Unix | 1 | Unix & Mac OS X baris baru - \n |
| Mac | 2 | Mac (OS 9) baris baru - \r |

## Catatan

Contoh 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Lihat Juga

* Ruang Nama [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)