---
title: get_FontFallBackRulesCollection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili koleksi aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan oleh fungsionalitas fallback Baca IFontFallBackRulesCollection.
type: docs
weight: 27
url: /id/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metode


Mewakili koleksi aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan oleh fungsionalitas fallback Baca [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Catatan



```cpp
auto pres = MakeObject<Presentation>();
// Mendapatkan koleksi aturan yang kosong atau telah diinisialisasi sebelumnya dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// menambahkan aturan ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// atau
// inisialisasi instance baru dari koleksi aturan
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// menambahkan aturan ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// dan mengganti koleksi yang ada dengan yang baru di FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Kelas [FontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)