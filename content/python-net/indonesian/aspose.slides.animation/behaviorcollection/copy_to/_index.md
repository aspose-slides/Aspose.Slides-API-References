---
title: copy_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Menyalin elemen-elemen dari **System.Collections.Generic.ICollection`1** ke sebuah **System.Array**, dimulai pada indeks **System.Array** tertentu.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| array | **List[IBehavior]** | Array satu dimensi **System.Array** yang menjadi tujuan elemen-elemen yang disalin dari **System.Collections.Generic.ICollection`1**. **System.Array** harus menggunakan indeks berbasis nol. |
| array_index | **int** | Indeks berbasis nol dalam `array` tempat penyalinan dimulai. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` kurang dari 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Jumlah elemen dalam **System.Collections.Generic.ICollection`1** sumber lebih besar daripada ruang yang tersedia dari `array_index` hingga akhir `array` tujuan. |



### Lihat Juga
* kelas [`BehaviorCollection`](/slides/python-net/id/aspose.slides.animation/behaviorcollection)
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* pustaka [`Aspose.Slides`](/slides/python-net)