---
title: get_ReadOnlyRecommended()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan rekomendasi hanya-baca. Baca bool.
type: docs
weight: 79
url: /id/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metode

Mendapatkan rekomendasi baca-saja. Baca **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Catatan

Kode contoh berikut menunjukkan cara mengatur PowerPoint [Presentation](../../presentation/) menjadi Baca-Saja di C# menggunakan [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)