---
title: check_write_protection method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Memeriksa apakah kata sandi untuk memodifikasi benar untuk presentasi yang dilindungi penulisan.

### Mengembalikan

True jika presentasi dilindungi penulisan dan kata sandinya benar. False jika tidak.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | **str** | Kata sandi yang akan diperiksa. |

### Catatan

1. Anda harus memeriksa properti [`PresentationInfo.is_write_protected`](/slides/python-net/id/aspose.slides/presentationinfo/is_write_protected) sebelum memanggil metode ini.
2. Ketika kata sandi bernilai None atau kosong, metode ini mengembalikan false.

### Pengecualian

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Lihat Juga
* kelas [`PresentationInfo`](/slides/python-net/id/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)