---
title: check_password method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi terbuka.

### Mengembalikan

True jika presentasi dilindungi dengan kata sandi terbuka dan kata sandi tersebut benar, dan false sebaliknya.



```python
def check_password(self, password):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | **str** | Kata sandi yang akan diperiksa. |

### Catatan

Ketika kata sandi adalah None atau kosong, metode ini mengembalikan false.

### Pengecualian

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Lihat Juga
* kelas [`PresentationInfo`](/slides/python-net/id/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)