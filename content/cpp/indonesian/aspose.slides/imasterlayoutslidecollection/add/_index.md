---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan slide tata letak baru ke akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metode


Menambahkan slide tata letak baru ke akhir koleksi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Jenis tata letak untuk tata letak baru. Jenis tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jenis tata letak lain tidak didukung saat ini: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilempar. Jika parameter null diberikan, maka nama akan dihasilkan secara otomatis berdasarkan jenis tata letak yang diberikan (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Nilai Kembali

Slide yang ditambahkan.

## Catatan

1) Tata letak yang ditambahkan untuk nilai [SlideLayoutType::Custom](../../slidelayouttype/) dari *layoutType* tidak mengandung placeholder dan tidak ada bentuk. 2) Analogi dari metode ini adalah metode [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) yang diakses melalui properti [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Lihat Juga

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [String](../../../system/string/)
* Kelas [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)