---
title: get_MasterTheme()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan tema master. Hanya baca Theme::IMasterTheme."
type: docs
weight: 404
url: /id/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metode


Mengembalikan tema master. Hanya Baca [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Catatan


Contoh berikut menunjukkan cara mengubah efek tema dengan mengubah bagian-bagian elemen PowerPoint [Presentation](../). 
```cpp
// Membuat objek presentasi yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Kelas [Presentation](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)