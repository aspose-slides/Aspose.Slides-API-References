---
title: register_ink_effect_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Mendaftarkan gambar ke koleksi gambar khusus yang digunakan untuk mensimulasikan efek visual pada kuas tinta.
            Gambar ini digunakan saat merender tinta dengan nilai [`InkEffectType`](/slides/python-net/id/aspose.slides.ink/inkeffecttype) tertentu,
            seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengendalikan bagaimana setiap efek tinta muncul.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/id/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/id/aspose.slides/iimage) |  |

### Catatan

Metode ini memungkinkan mengganti tekstur efek tinta default dengan tekstur yang didefinisikan pengguna, yang sangat berguna ketika aset default dibatasi oleh lisensi atau tidak tersedia pada waktu berjalan. Setiap pasangan nilai yang terdaftar harus mengaitkan nilai [`InkEffectType`](/slides/python-net/id/aspose.slides.ink/inkeffecttype) dengan objek [`IImage`](/slides/python-net/id/aspose.slides/iimage) yang sesuai (mis., Bitmap, atau antarmuka gambar Aspose).


### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`Ink`](/slides/python-net/id/aspose.slides.ink/ink)
* enumerasi [`InkEffectType`](/slides/python-net/id/aspose.slides.ink/inkeffecttype)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* pustaka [`Aspose.Slides`](/slides/python-net)