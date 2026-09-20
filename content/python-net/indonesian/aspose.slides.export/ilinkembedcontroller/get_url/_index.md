---
title: get_url method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Mengembalikan URL ke objek eksternal.
            Metode ini selalu dipanggil jika **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** mengembalikan [`LinkEmbedDecision.LINK`](/slides/python-net/id/aspose.slides.export/linkembeddecision/LINK) dan dapat dipanggil jika **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** mengembalikan [`LinkEmbedDecision.EMBED`](/slides/python-net/id/aspose.slides.export/linkembeddecision/EMBED) tetapi penyisipan tidak memungkinkan.
            Dapat dipanggil berkali-kali untuk id objek yang sama.

### Mengembalikan

Url of external object or None if this object should be ignored.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | **int** | Id objek. Id ini bersifat unik pada seluruh operasi penyimpanan. |
| referrer | **int** | id objek yang merujuk atau 0, jika objek dirujuk oleh dokumen akar. Dapat digunakan untuk membuat tautan relatif. |



### Lihat Juga
* kelas [`ILinkEmbedController`](/slides/python-net/id/aspose.slides.export/ilinkembedcontroller)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)