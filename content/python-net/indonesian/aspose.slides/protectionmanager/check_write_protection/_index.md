---
title: check_write_protection method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Menentukan apakah presentasi dilindungi kata sandi untuk dimodifikasi.

### Mengembalikan

True jika kata sandi valid; jika tidak, false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | **str** | Kata sandi untuk pemeriksaan. |

### Catatan

1. Anda harus memeriksa properti [`ProtectionManager.is_write_protected`](/slides/python-net/id/aspose.slides/protectionmanager/is_write_protected) sebelum memanggil metode ini.
            2. Ketika kata sandi None atau kosong, metode ini mengembalikan false.



### Lihat Juga
* kelas [`ProtectionManager`](/slides/python-net/id/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)