---
title: from_name method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Membuat warna dari nama yang ditentukan dari warna yang telah ditetapkan.<br/>Pencarian tidak sensitif huruf besar/kecil dan mengabaikan garis bawah serta spasi: `"LightBlue"`, `"lightblue"` dan `"light_blue"` semuanya menjadi `Color.light_blue`. Lihat halaman kelas [`Color`](/slides/python-net/id/aspose.slides/color) untuk daftar warna yang telah ditetapkan.

### Mengembalikan

Warna yang dinamai.



```python
@staticmethod
def from_name(name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | **str** | Sebuah string yang merupakan nama dari warna yang telah ditetapkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **ValueError** | Nama bukan nama dari warna yang telah ditetapkan. |
| **TypeError** | Nama bukan string. |



### Lihat Juga
* kelas [`Color`](/slides/python-net/id/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)