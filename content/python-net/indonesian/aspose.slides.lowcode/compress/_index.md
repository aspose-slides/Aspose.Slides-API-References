---
title: Compress class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/compress/
---
## Compress kelas

Mewakili sekumpulan metode yang dimaksudkan untuk mengompres [`Presentation`](/slides/python-net/id/aspose.slides/presentation).

Tipe Compress menampilkan anggota berikut:

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/id/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Mengurangi ukuran presentasi dengan menerapkan semua langkah kompresi yang tersedia:<br/>            <br/>* Menghapus master slide yang tidak terpakai **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Menghapus layout slide yang tidak terpakai **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Menyimpan hanya glyph yang benar-benar digunakan dalam font yang disematkan **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Mengurangi resolusi gambar menjadi 150 DPI dan menghapus area gambar yang terpotong **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/id/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Melakukan kompresi [`Presentation`](/slides/python-net/id/aspose.slides/presentation) dengan menghapus master slide yang tidak terpakai. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/id/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Melakukan kompresi [`Presentation`](/slides/python-net/id/aspose.slides/presentation) dengan menghapus layout slide yang tidak terpakai. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/id/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Melakukan kompresi [`Presentation`](/slides/python-net/id/aspose.slides/presentation) dengan menghapus karakter yang tidak terpakai dari font yang disematkan. |
| [`compress_images(presentation, resolution)`](/slides/python-net/id/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Mengurangi resolusi gambar dalam presentasi dan menghapus area yang terpotong,<br/>            mirip dengan “Compress Pictures” pada PowerPoint yang diterapkan pada semua gambar.<br/>            Gambar pada slide, layout slide, dan master slide diproses, termasuk gambar di dalam grup bentuk<br/>            dan isian gambar pada bentuk. |


### Lihat Juga
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* perpustakaan [`Aspose.Slides`](/slides/python-net)