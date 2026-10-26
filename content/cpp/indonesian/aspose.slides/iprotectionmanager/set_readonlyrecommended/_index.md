---
title: set_ReadOnlyRecommended()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur rekomendasi baca-saja. Menulis bool.
type: docs
weight: 92
url: /id/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metode


Mengatur rekomendasi baca-saja. Menulis **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Catatan


```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IProtectionManager](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)