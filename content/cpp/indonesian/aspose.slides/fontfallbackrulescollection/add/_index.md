---
title: Add()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan aturan FallBack yang ditentukan ke akhir koleksi.
type: docs
weight: 40
url: /id/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metode

Menambahkan aturan FallBack yang ditentukan ke akhir koleksi.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Aturan yang ditentukan untuk penambahan |
## Catatan



```cpp
auto pres = MakeObject<Presentation>();
//Mendapatkan koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Menambahkan aturan baru ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRule](../../ifontfallbackrule/)
* Kelas [FontFallBackRulesCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)