---
title: Add()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan slide tata letak baru ke presentasi.
type: docs
weight: 14
url: /id/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method


Menambahkan slide tata letak baru ke presentasi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master untuk tata letak baru. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilempar. Jika parameter null diberikan, maka nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Nilai Kembalian

Slide yang ditambahkan.

## Catatan

1) Tata letak yang ditambahkan untuk nilai [SlideLayoutType::Custom](../../slidelayouttype/) dari *layoutType* tidak mengandung placeholder dan tidak ada bentuk. 2) Analogi dari metode ini adalah metode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) yang diakses dengan properti [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Lihat Juga

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterSlide](../../imasterslide/)
* Kelas [String](../../../system/string/)
* Kelas [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)