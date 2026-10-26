---
title: Encrypt()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengenkripsi Presentasi dengan kata sandi yang ditentukan.
type: docs
weight: 105
url: /id/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) method

Mengenkripsi [Presentation](../../presentation/) dengan kata sandi yang ditentukan.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Kata sandi. |

## Catatan

Kode contoh berikut menunjukkan cara mengenkripsi sebuah PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)