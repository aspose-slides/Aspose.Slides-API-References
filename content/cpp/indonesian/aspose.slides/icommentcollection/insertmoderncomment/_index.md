---
title: InsertModernComment()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan komentar modern baru ke dalam koleksi pada indeks yang ditentukan.
type: docs
weight: 53
url: /id/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

Menyisipkan komentar modern baru ke dalam koleksi pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks elemen dalam koleksi tempat komentar modern harus disisipkan. |
| text | [System::String](../../../system/string/) | Teks polos dari komentar modern baru. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) pada slide yang berhubungan dengan komentar modern baru. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | [System::DateTime](../../../system/datetime/) | Waktu pembuatan komentar modern. |

### Nilai Kembalian

Komentar modern yang disisipkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IModernComment](../../imoderncomment/)
* Kelas [String](../../../system/string/)
* Kelas [ISlide](../../islide/)
* Kelas [IShape](../../ishape/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)