---
title: set_FontFallBackRulesCollection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font sehingga substitusi yang tepat dapat dilakukan melalui fungsi fallback. Tulis IFontFallBackRulesCollection.
type: docs
weight: 40
url: /id/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) metode

Mewakili koleksi FontFallBack milik pengguna untuk mengelola koleksi font guna substitusi yang tepat melalui fungsi fallback. Tulis [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
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
// dan menggantikan koleksi yang ada dengan yang baru di FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Kelas [IFontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)