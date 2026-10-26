---
title: InsertComment()
second_title: Referensi API Aspose.Slides untuk C++
description: Masukkan komentar baru ke dalam koleksi pada indeks yang ditentukan.
type: docs
weight: 79
url: /id/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metode

Masukkan komentar baru ke dalam koleksi pada indeks yang ditentukan.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks elemen dalam koleksi tempat komentar harus disisipkan. |
| text | [System::String](../../../system/string/) | Teks biasa dari komentar baru. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dalam presentasi tempat menambahkan komentar baru. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | [System::DateTime](../../../system/datetime/) | Waktu pembuatan komentar. |

### Nilai Kembalian

Komentar yang disisipkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [String](../../../system/string/)
* Kelas [ISlide](../../islide/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [CommentCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)