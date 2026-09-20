---
title: delete_row method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Menghapus baris yang ditentukan


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| row_index | **int** | Indeks berbasis nol dari baris yang akan dihapus. |

### Exceptions

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika Anda mencoba menghapus baris tunggal terakhir dalam matriks |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Jika rowIndex kurang dari nol atau lebih besar atau sama dengan RowCount |



### Lihat Juga
* kelas [`MathMatrix`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)