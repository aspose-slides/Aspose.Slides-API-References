---
title: delete_column method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Menghapus kolom yang ditentukan


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| column_index | **int** | Indeks berbasis nol dari kolom yang akan dihapus. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika Anda mencoba menghapus kolom tunggal terakhir dalam matriks |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Jika columnIndex kurang dari nol atau lebih besar atau sama dengan ColumnCount |



### Lihat Juga
* kelas [`MathMatrix`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)