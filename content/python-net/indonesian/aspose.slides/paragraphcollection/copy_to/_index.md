---
title: copy_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Menyalin elemen dari **System.Collections.Generic.ICollection`1** ke **System.Array**, dimulai pada indeks **System.Array** tertentu.

```python
def copy_to(self, array, array_index):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| array | **List[IParagraph]** | **System.Array** satu dimensi yang menjadi tujuan elemen yang disalin dari **System.Collections.Generic.ICollection`1**. **System.Array** harus menggunakan pengindeksan berbasis nol. |
| array_index | **int** | Indeks berbasis nol dalam `array` tempat penyalinan dimulai. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` kurang dari 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Jumlah elemen dalam sumber **System.Collections.Generic.ICollection`1** lebih besar daripada ruang yang tersedia dari `array_index` hingga akhir `array` tujuan. |

### Lihat Juga
* kelas [`ParagraphCollection`](/slides/python-net/id/aspose.slides/paragraphcollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)