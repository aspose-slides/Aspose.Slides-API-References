---
title: Insert()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 40
url: /id/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metode


Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilempar. Jika parameter null diberikan, maka nama akan dibuat secara otomatis berdasarkan tipe tata letak yang diberikan (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Nilai Kembalian

Slide yang disisipkan.

## Catatan



Tata letak yang disisipkan untuk nilai [SlideLayoutType::Custom](../../slidelayouttype/) dari *layoutType* tidak mengandung placeholder dan tidak mengandung bentuk. 

## Lihat Juga

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [String](../../../system/string/)
* Kelas [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)