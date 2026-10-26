---
title: WriteShapeEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Dipanggil sebelum rendering shape. Dipanggil sekali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.
type: docs
weight: 79
url: /id/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metode


Dipanggil sebelum rendering shape. Dipanggil sekali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objek keluaran. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) yang dirender terakhir. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IHtmlGenerator](../../ihtmlgenerator/)
* Kelas [IShape](../../../aspose.slides/ishape/)
* Kelas [EmbedAllFontsHtmlController](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)