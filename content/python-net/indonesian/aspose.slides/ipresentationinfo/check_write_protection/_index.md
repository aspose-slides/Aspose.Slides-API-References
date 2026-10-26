---
title: check_write_protection method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Memeriksa apakah kata sandi untuk memodifikasi presentasi yang dilindungi penulisan sudah benar.

### Mengembalikan

True jika presentasi dilindungi penulisan dan kata sandi benar. False jika tidak.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Deskripsi |
| :- | :- | :- |
| password | **str** | Kata sandi yang akan diperiksa. |

### Catatan

1. Anda harus memeriksa properti [`IPresentationInfo.is_write_protected`](/slides/python-net/id/aspose.slides/ipresentationinfo/is_write_protected) sebelum memanggil metode ini.
            2. Ketika kata sandi adalah None atau kosong, metode ini mengembalikan false.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Lihat Juga
* kelas [`IPresentationInfo`](/slides/python-net/id/aspose.slides/ipresentationinfo)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)