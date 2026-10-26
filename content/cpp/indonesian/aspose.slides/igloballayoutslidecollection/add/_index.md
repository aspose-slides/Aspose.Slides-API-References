---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan slide tata letak baru ke presentasi.
type: docs
weight: 14
url: /id/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metode

Menambahkan slide tata letak baru ke presentasi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master untuk tata letak baru. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Jenis tata letak untuk tata letak baru. Jenis tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jenis tata letak lain tidak didukung saat ini: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan. Jika parameter null diberikan maka nama akan dihasilkan secara otomatis berdasarkan jenis tata letak yang diberikan (misalnya \"Title Slide\" atau \"1_Title Slide\", \"2_..\", dll.). |

### Nilai Kembalian

Slide yang ditambahkan.

## Catatan

1) Tata letak yang ditambahkan untuk nilai [SlideLayoutType::Custom](../../slidelayouttype/) dari *layoutType* tidak mengandung placeholder dan tidak ada bentuk. 2) Analogi metode ini adalah metode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) yang diakses dengan properti [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Lihat Juga

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterSlide](../../imasterslide/)
* Kelas [String](../../../system/string/)
* Kelas [IGlobalLayoutSlideCollection](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)