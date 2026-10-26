---
title: CheckWriteProtection()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah kata sandi untuk memodifikasi benar pada presentasi yang dilindungi penulisan.
type: docs
weight: 66
url: /id/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metode

Memeriksa apakah kata sandi untuk memodifikasi benar pada presentasi yang dilindungi penulisan.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kata sandi yang akan diperiksa. |

## Nilai Kembali

True jika presentasi dilindungi penulisan dan kata sandi benar. False jika tidak.

## Catatan

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Anda harus memeriksa properti [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) sebelum memanggil metode ini.
1. Ketika kata sandi null atau kosong, metode ini mengembalikan false.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)