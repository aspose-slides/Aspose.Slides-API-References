---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Menambahkan slide tata letak baru ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype) | Jenis tata letak untuk tata letak baru.<br/><br/>            Jenis tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Jenis tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan.<br/><br/>            Jika parameter None diberikan maka nama akan dihasilkan secara otomatis berdasarkan jenis tata letak yang diberikan <br/><br/>            (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Catatan

1) Tata letak yang ditambahkan untuk nilai SlideLayoutType.Custom dari `layout_type` tidak berisi placeholder dan tidak memiliki bentuk.
2) Analogi dari metode ini adalah metode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** yang diakses melalui properti [`IPresentation.layout_slides`](/slides/python-net/id/aspose.slides/ipresentation/layout_slides).

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Dilemparkan jika nilai parameter `layout_type` yang tidak didukung diberikan. Jenis tata letak yang tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika nilai nama tata letak `layout_name` sudah digunakan dalam <br/>            koleksi tata letak ini. |



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`MasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/masterlayoutslidecollection)
* enumerasi [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)