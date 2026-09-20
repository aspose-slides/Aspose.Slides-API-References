---
title: set_size method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Mengatur ukuran slide berdasarkan tipe dan menyesuaikan konten yang ada.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/id/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Catatan

Memberikan nilai selain [`SlideSizeType.CUSTOM`](/slides/python-net/id/aspose.slides/slidesizetype/CUSTOM) menyesuaikan [`ISlideSize.size`](/slides/python-net/id/aspose.slides/islidesize/size) berdasarkan tipe yang dipilih, sambil mempertahankan [`ISlideSize.orientation`](/slides/python-net/id/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Mengatur dimensi slide secara eksplisit dan menyesuaikan konten yang ada.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Catatan

Ini mengatur ulang properti [`ISlideSize.type`](/slides/python-net/id/aspose.slides/islidesize/type) menjadi [`SlideSizeType.CUSTOM`](/slides/python-net/id/aspose.slides/slidesizetype/CUSTOM) dan menetapkan [`ISlideSize.orientation`](/slides/python-net/id/aspose.slides/islidesize/orientation).



### Lihat Juga
* kelas [`ISlideSize`](/slides/python-net/id/aspose.slides/islidesize)
* enumerasi [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype)
* enumerasi [`SlideSizeType`](/slides/python-net/id/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)