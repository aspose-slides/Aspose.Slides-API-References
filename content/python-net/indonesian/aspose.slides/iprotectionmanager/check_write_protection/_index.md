---
title: check_write_protection method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Menentukan apakah presentasi dilindungi kata sandi untuk diubah.

### Mengembalikan

True jika password valid; sebaliknya, false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | **str** | Password untuk memeriksa. |

### Catatan

1. Anda harus memeriksa properti [`IProtectionManager.is_write_protected`](/slides/python-net/id/aspose.slides/iprotectionmanager/is_write_protected) sebelum memanggil metode ini.
            2. Ketika password bernilai None atau kosong, metode ini mengembalikan false.



### Lihat Juga
* kelas [`IProtectionManager`](/slides/python-net/id/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)