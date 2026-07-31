---
title: set_ReadOnlyRecommended()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur rekomendasi hanya-baca. Tulis bool.
type: docs
weight: 92
url: /id/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metode

Mengatur rekomendasi hanya-baca. Tulis **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Keterangan

Kode contoh berikut menunjukkan cara mengatur PowerPoint [Presentation](../../presentation/) menjadi Read-Only dalam C# menggunakan [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)