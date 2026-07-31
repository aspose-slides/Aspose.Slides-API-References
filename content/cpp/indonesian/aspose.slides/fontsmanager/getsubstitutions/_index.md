---
title: GetSubstitutions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan informasi tentang font yang akan diganti pada proses rendering presentasi.
type: docs
weight: 66
url: /id/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() metode


Mendapatkan informasi tentang font yang akan diganti pada proses rendering presentasi.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### Nilai Kembalian

Koleksi semua substitusi font [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metode


Mendapatkan informasi tentang font yang akan diganti selama proses rendering slide yang ditentukan.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array indeks slide untuk mengambil informasi substitusi font, dimulai dari 1. |

### Nilai Kembalian

Koleksi semua substitusi font ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) untuk slide yang ditentukan.
## Catatan




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)