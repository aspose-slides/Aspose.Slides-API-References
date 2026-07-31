---
title: CheckWriteProtection()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan apakah sebuah presentasi dilindungi kata sandi untuk diubah.
type: docs
weight: 157
url: /id/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metode

Menentukan apakah sebuah presentasi dilindungi kata sandi untuk diubah.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kata sandi untuk memeriksa. |

### Nilai Kembali

True jika kata sandi valid; jika tidak, false.

## Keterangan

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Anda harus memeriksa properti [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) sebelum memanggil metode ini.
1. Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)