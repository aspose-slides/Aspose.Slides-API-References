---
title: GetSubstitutions()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan informasi tentang font yang akan diganti pada rendering presentasi.
type: docs
weight: 66
url: /id/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metode


Mendapatkan informasi tentang font yang akan diganti pada rendering presentasi.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Nilai Kembali

Koleksi semua substitusi font [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metode


Mendapatkan informasi tentang font yang akan diganti selama rendering slide yang ditentukan.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array indeks slide yang untuknya mengambil informasi substitusi font, dimulai dari 1. |

### Nilai Kembali

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
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Kelas [IFontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)