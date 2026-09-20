---
title: insert method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.

### Mengembalikan

Slide yang disisipkan.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| layout_type | [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype) | Tipe tata letak untuk tata letak baru.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan.<br/><br/>            Jika parameter None diberikan maka nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan <br/><br/>            (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Catatan

Layout yang disisipkan untuk nilai SlideLayoutType.Custom dari `layout_type` tidak memiliki placeholder dan tidak ada bentuk.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Dilemparkan jika nilai `layout_type` yang tidak didukung diberikan. Tipe tata letak yang tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika nilai nama tata letak `layout_name` sudah digunakan dalam <br/>            koleksi tata letak ini. |

### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`MasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/masterlayoutslidecollection)
* enumerasi [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)