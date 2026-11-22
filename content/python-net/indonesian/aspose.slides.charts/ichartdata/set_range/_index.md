---
title: set_range method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Atur rentang data diagram. Seri dan kategori akan diperbarui berdasarkan rentang data baru.
Jika jumlah seri dalam rentang data lebih besar dari jumlah seri dalam data diagram, maka seri tambahan dengan tipe yang sama dengan seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi.

```python
def set_range(self, formula):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| formula | **str** | Rumus rentang data sel. Contoh: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula bernilai None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula memiliki format yang tidak tepat. |

### Lihat Juga
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)