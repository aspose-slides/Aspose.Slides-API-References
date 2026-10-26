---
title: InsertComment()
second_title: Referensi API Aspose.Slides untuk C++
description: Masukkan komentar baru ke dalam koleksi pada indeks yang ditentukan.
type: docs
weight: 40
url: /id/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Masukkan komentar baru ke dalam koleksi pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks elemen dalam koleksi tempat komentar harus disisipkan. |
| text | [System::String](../../../system/string/) | Teks biasa dari komentar baru. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dalam presentasi di mana menambahkan komentar baru. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | [System::DateTime](../../../system/datetime/) | Waktu pembuatan komentar. |

### Return Value

Komentar yang disisipkan.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [String](../../../system/string/)
* Kelas [ISlide](../../islide/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)