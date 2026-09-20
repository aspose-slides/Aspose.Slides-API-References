---
title: insert method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.

### Mengembalikan

Slide yang dimasukkan.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| layout_type | [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype) | Jenis tata letak untuk tata letak baru.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan maka ArgumentException akan dilemparkan.<br/><br/>            Jika parameter None diberikan maka nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan <br/><br/>            (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

### Keterangan

Tata letak yang dimasukkan untuk nilai SlideLayoutType.Custom dari `layout_type` tidak mengandung placeholder dan tidak ada bentuk.

### Eksepsi

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Dilemparkan jika nilai parameter `layout_type` yang tidak didukung diberikan. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika nilai nama tata letak `layout_name` sudah digunakan dalam <br/>            koleksi tata letak ini. |



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection)
* enumerasi [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)