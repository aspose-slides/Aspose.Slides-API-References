---
title: equals method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Menentukan apakah dua instance IBaseSlide sama.
            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.
            Dua slide dianggap sama jika semua shape, style, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini pada Placeholder Tanggal.

### Mengembalikan

**true**  jika IBaseSlide yang ditentukan sama dengan IBaseSlide saat ini; 
            jika tidak, **false** .

```python
def equals(self, slide):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide) | IBaseSlide untuk dibandingkan dengan IBaseSlide saat ini. |

### Lihat Juga
* kelas [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide)
* kelas [`MasterHandoutSlide`](/slides/python-net/id/aspose.slides/masterhandoutslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)