---
title: CheckWriteProtection()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi penulisan.
type: docs
weight: 66
url: /id/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metode


Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi penulisan.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kata sandi yang akan diperiksa. |

### Nilai Kembalian

True jika presentasi dilindungi penulisan dan kata sandi benar. False sebaliknya.
## Catatan



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Anda harus memeriksa properti [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) sebelum memanggil metode ini.
1. Ketika password bernilai null atau kosong, metode ini mengembalikan false.



## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [PresentationInfo](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)