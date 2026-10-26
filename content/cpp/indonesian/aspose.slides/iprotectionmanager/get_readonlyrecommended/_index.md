---
title: get_ReadOnlyRecommended()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan rekomendasi read-only. Membaca bool.
type: docs
weight: 79
url: /id/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metode

Mendapatkan rekomendasi read-only. Membaca **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)