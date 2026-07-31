---
title: WriteShapeEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Dipanggil sebelum rendering bentuk. Dipanggil sekali untuk setiap bentuk. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.
type: docs
weight: 66
url: /id/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metode

Dipanggil sebelum rendering bentuk. Dipanggil sekali untuk setiap bentuk. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objek output. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) yang dirender terakhir. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IHtmlGenerator](../../ihtmlgenerator/)
* Kelas [IShape](../../../aspose.slides/ishape/)
* Kelas [IHtmlFormattingController](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)