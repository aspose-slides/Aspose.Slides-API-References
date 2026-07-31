---
title: MarkdownImageSavingHandler
second_title: Referensi API Aspose.Slides untuk C++
description: Dipanggil untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. Kembalikan true untuk menggunakan tautan yang ditentukan, atau false untuk menerapkan logika penyimpanan default.
type: docs
weight: 300
url: /id/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef

Dipanggil untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. 

Kembalikan **true** untuk menggunakan *tautan* yang ditentukan,

atau **false** untuk menerapkan logika penyimpanan default.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```

## Lihat Juga

* Kelas [MarkdownSaveOptions](../)
* RuangNama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)