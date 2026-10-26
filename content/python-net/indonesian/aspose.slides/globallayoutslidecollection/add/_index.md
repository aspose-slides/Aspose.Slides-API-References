---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Menambahkan slide tata letak baru ke presentasi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Slide master untuk tata letak baru. |
| layout_type | [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype) | Tipe tata letak untuk tata letak baru.<br/><br/>            Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilempar.<br/><br/>            Jika parameter None diberikan maka nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan <br/><br/>            (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Catatan

1) Tata letak yang ditambahkan untuk nilai SlideLayoutType.Custom dari `layout_type` tidak mengandung placeholder dan tidak memiliki shape.  
2) Analogi dari metode ini adalah metode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** yang diakses melalui properti [`IMasterSlide.layout_slides`](/slides/python-net/id/aspose.slides/imasterslide/layout_slides).

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Dilempar jika nilai parameter `layout_type` yang tidak didukung diberikan. Tipe tata letak yang tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dilempar jika `master` bernilai None. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika `master` berasal dari presentasi lain. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika nilai nama tata letak `layout_name` sudah digunakan dalam koleksi tata letak `master`. |



### Lihat Juga
* kelas [`GlobalLayoutSlideCollection`](/slides/python-net/id/aspose.slides/globallayoutslidecollection)
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* enumerasi [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)