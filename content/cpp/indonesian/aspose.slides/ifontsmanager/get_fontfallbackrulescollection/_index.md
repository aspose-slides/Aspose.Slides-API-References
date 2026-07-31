---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola kumpulan font demi substitusi yang tepat melalui fungsi fallback. Baca IFontFallBackRulesCollection.
type: docs
weight: 27
url: /id/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metode


Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola kumpulan font demi substitusi yang tepat melalui fungsi fallback Baca [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Keterangan



```cpp
auto pres = MakeObject<Presentation>();
// Mendapatkan koleksi aturan kosong atau terinisialisasi sebelumnya dari FontsManager
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
* Kelas [IFontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)