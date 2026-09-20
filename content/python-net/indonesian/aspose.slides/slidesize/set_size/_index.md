---
title: set_size method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/id/aspose.slides/slidesizetype) | Ukuran slide yang telah ditentukan untuk diterapkan. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype) | Mode penskalaan konten yang akan digunakan. |

### Catatan

Menetapkan nilai apa pun selain [`SlideSizeType.CUSTOM`](/slides/python-net/id/aspose.slides/slidesizetype/CUSTOM) menyesuaikan [`SlideSize.size`](/slides/python-net/id/aspose.slides/slidesize/size) berdasarkan tipe yang dipilih, sambil mempertahankan [`SlideSize.orientation`](/slides/python-net/id/aspose.slides/slidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Mengatur dimensi slide secara eksplisit dan menskalakan konten yang ada.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | **float** | Lebar slide baru, dalam poin. |
| height | **float** | Tinggi slide baru, dalam poin. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype) | Mode penskalaan konten yang akan digunakan. |

### Catatan

Ini mengatur ulang properti [`SlideSize.type`](/slides/python-net/id/aspose.slides/slidesize/type) menjadi [`SlideSizeType.CUSTOM`](/slides/python-net/id/aspose.slides/slidesizetype/CUSTOM) dan menetapkan [`SlideSize.orientation`](/slides/python-net/id/aspose.slides/slidesize/orientation).



### Lihat Juga
* kelas [`SlideSize`](/slides/python-net/id/aspose.slides/slidesize)
* enumerasi [`SlideSizeScaleType`](/slides/python-net/id/aspose.slides/slidesizescaletype)
* enumerasi [`SlideSizeType`](/slides/python-net/id/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)