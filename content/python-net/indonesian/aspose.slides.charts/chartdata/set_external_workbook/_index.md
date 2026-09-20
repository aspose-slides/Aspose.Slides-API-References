---
title: set_external_workbook method
second_title: Aspose.Slides untuk Python via Referensi API .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari buku kerja target.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| workbook_path | **str** | Jalur ke buku kerja target |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Buku kerja eksternal tidak tersedia atau tidak dapat dimuat. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Menetapkan buku kerja eksternal sebagai sumber data untuk diagram.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| workbook_path | **str** | Jalur ke buku kerja target |
| update_chart_data | **bool** | Jika nilai false hanya jalur buku kerja yang akan diperbarui. <br/><br/>             Data diagram tidak akan dimuat dan diperbarui dari buku kerja target. Dapat digunakan ketika buku kerja target tidak ada atau tidak tersedia.<br/><br/>             Jika nilai true data diagram akan diperbarui dari buku kerja target. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Buku kerja eksternal tidak tersedia atau tidak dapat dimuat. |

### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)