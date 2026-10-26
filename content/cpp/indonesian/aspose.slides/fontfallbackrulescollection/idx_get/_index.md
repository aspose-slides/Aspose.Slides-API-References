---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan aturan pada indeks yang ditentukan. Hanya-baca IFontFallBackRule.
type: docs
weight: 66
url: /id/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metode

Mendapatkan aturan pada indeks yang ditentukan. Hanya-baca [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Catatan

```cpp
auto pres = MakeObject<Presentation>();
//Mendapatkan koleksi aturan kosong atau telah diinisialisasi dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Menambahkan beberapa aturan ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Mengambil objek aturan pertama dalam koleksi
auto firstRule = rulesList->idx_get(0);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRule](../../ifontfallbackrule/)
* Kelas [FontFallBackRulesCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)