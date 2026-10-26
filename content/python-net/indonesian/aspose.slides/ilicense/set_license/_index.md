---
title: set_license method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Memberi lisensi pada komponen.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| license_name | **str** | Dapat berupa nama file lengkap atau singkat atau nama sumber daya yang disematkan.<br/><br/>Gunakan string kosong untuk beralih ke mode evaluasi. |

### Catatan

Mencoba menemukan lisensi di lokasi berikut:


1. Jalur eksplisit.

2. Folder assembly komponen.

3. Folder assembly pemanggil klien.

4. Folder assembly entri.

5. Sumber daya yang disematkan di assembly pemanggil klien.

**Catatan:** Pada .NET Compact Framework, mencoba menemukan lisensi hanya di lokasi berikut:


1. Jalur eksplisit.

2. Sumber daya yang disematkan di assembly pemanggil klien.


## set_license(self, stream) {#iorawiobase}
Memberi lisensi pada komponen.


```python
def set_license(self, stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran yang berisi lisensi. |

### Catatan

Gunakan metode ini untuk memuat lisensi dari aliran.



### Lihat Juga
* kelas [`ILicense`](/slides/python-net/id/aspose.slides/ilicense)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)