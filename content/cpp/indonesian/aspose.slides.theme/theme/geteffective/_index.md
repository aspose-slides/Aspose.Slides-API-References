---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan data tema yang efektif dengan pewarisan yang diterapkan.
type: docs
weight: 53
url: /id/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metode


Mendapatkan data tema yang efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Nilai Kembalian

Sebuah [IThemeEffectiveData](../../ithemeeffectivedata/).
## Catatan



Contoh ini menunjukkan cara mendapatkan properti tema yang efektif.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IThemeEffectiveData](../../ithemeeffectivedata/)
* Kelas [Theme](../)
* Ruang Nama [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)