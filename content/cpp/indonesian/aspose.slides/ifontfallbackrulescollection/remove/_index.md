---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus kemunculan pertama dari aturan FallBack tertentu dalam koleksi.
type: docs
weight: 27
url: /id/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metode


Menghapus kemunculan pertama dari aturan FallBack tertentu dari koleksi.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Aturan yang akan dihapus dari koleksi. |
## Catatan



```cpp
auto pres = MakeObject<Presentation>();
//Mendapatkan koleksi aturan kosong atau sudah diinisialisasi dari FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Menambahkan beberapa aturan ke koleksi
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Mengambil objek aturan pertama dalam koleksi
auto firstRule = rulesList->idx_get(0);
//Menghapus
rulesList->Remove(firstRule);
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontFallBackRule](../../ifontfallbackrule/)
* Kelas [IFontFallBackRulesCollection](../)
* RuangNama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)