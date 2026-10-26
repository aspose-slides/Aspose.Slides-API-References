---
title: AddModernComment()
second_title: Aspose.Slides untuk Referensi API C++
description: Tambahkan komentar modern baru di akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Tambahkan komentar modern baru di akhir koleksi.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks biasa dari komentar modern baru. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) pada slide yang dikaitkan dengan komentar modern baru. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | [System::DateTime](../../../system/datetime/) | Waktu pembuatan komentar modern. |

### Nilai Kembalian

Added modern comment.
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IModernComment](../../imoderncomment/)
* Kelas [String](../../../system/string/)
* Kelas [ISlide](../../islide/)
* Kelas [IShape](../../ishape/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [ICommentCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)