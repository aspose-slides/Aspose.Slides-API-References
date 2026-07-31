---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan aturan FallBack baru ke akhir koleksi.
type: docs
weight: 14
url: /id/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metode


Tambahkan aturan FallBack baru ke akhir koleksi.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Aturan yang ditentukan untuk penambahan |
## Catatan



```cpp
auto pres = MakeObject<Presentation>();
//Mendapatkan koleksi aturan kosong atau sudah diinisialisasi dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Menambahkan aturan baru ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRule](../../ifontfallbackrule/)
* Kelas [IFontFallBackRulesCollection](../)
* RuangNama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)