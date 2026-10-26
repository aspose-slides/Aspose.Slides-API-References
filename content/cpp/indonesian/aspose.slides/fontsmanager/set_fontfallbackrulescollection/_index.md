---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili koleksi aturan FontFallBack milik pengguna untuk mengelola kumpulan font agar substitusi yang tepat dapat dilakukan oleh fungsi fallback. Tulis IFontFallBackRulesCollection.
type: docs
weight: 40
url: /id/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) method


Mewakili kumpulan aturan FontFallBack pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan oleh fungsi fallback. Tulis [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Catatan



```cpp
auto pres = MakeObject<Presentation>();
// Mendapatkan koleksi aturan kosong atau sudah diinisialisasi dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// menambahkan aturan ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// atau
// menginisialisasi instance baru dari koleksi aturan
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