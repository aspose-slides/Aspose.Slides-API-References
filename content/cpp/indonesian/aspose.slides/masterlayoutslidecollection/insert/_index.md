---
title: Insert()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 40
url: /id/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method

Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan ArgumentException akan dilempar. Jika parameter null diberikan maka nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan (misalnya \"Title Slide\" atau \"1_Title Slide\", \"2_..\", dll.). |

### Nilai Kembalian

Slide yang disisipkan.

## Catatan

Tata letak yang disisipkan untuk nilai [SlideLayoutType::Custom](../../slidelayouttype/) dari *layoutType* tidak mengandung placeholder dan tidak ada shape.

## Lihat Juga

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [String](../../../system/string/)
* Kelas [MasterLayoutSlideCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)