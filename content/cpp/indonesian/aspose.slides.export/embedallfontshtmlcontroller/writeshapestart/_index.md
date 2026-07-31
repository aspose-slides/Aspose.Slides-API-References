---
title: WriteShapeStart()
second_title: Referensi API Aspose.Slides untuk C++
description: Dipanggil sebelum rendering shape. Dipanggil sekali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.
type: docs
weight: 66
url: /id/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metode

Dipanggil sebelum rendering shape. Dipanggil sekali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objek output. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) yang akan dirender. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IHtmlGenerator](../../ihtmlgenerator/)
* Kelas [IShape](../../../aspose.slides/ishape/)
* Kelas [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)