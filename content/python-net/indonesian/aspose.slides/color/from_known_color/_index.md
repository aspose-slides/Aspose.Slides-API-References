---
title: from_known_color method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Membuat warna dari warna pra-definisi yang ditentukan.<br/>Ini satu-satunya cara untuk memperoleh warna sistem (seperti `KnownColor.CONTROL`): warna sistem tidak ditampilkan sebagai atribut `Color` karena nilainya bergantung pada tema desktop, sehingga dibaca dari runtime perpustakaan.

### Mengembalikan

Warna yang dibuat oleh metode ini.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| known_color | **KnownColor** | Elemen dari enumerasi `KnownColor` (sebuah `IntEnum` yang meniru .NET `System.Drawing.KnownColor`) atau nilai integernya. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **ValueError** | Nilai tersebut bukan anggota `KnownColor` yang valid. |



### Lihat Juga
* kelas [`Color`](/slides/python-net/id/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)