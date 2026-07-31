---
title: CheckWriteProtection()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi.
type: docs
weight: 157
url: /id/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metode

Menentukan apakah presentasi dilindungi password untuk dimodifikasi.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Password untuk memeriksa. |

### Nilai Kembali

True jika password valid; jika tidak, false.

## Catatan

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Anda harus memeriksa properti [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) sebelum memanggil metode ini.
1. Ketika password null atau kosong, metode ini mengembalikan false.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)