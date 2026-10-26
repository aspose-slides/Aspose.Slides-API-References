---
title: WriteShapeStart()
second_title: Referensi API Aspose.Slides for C++
description: Dipanggil sebelum rendering shape. Dipanggil satu kali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen HTML yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas gambar sebelumnya.
type: docs
weight: 53
url: /id/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metode

Dipanggil sebelum rendering shape. Dipanggil satu kali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas gambar sebelumnya.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
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
* Kelas [IHtmlFormattingController](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)