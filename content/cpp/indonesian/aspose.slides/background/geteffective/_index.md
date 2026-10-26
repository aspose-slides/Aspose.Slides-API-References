---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan data latar belakang yang efektif dengan pewarisan yang diterapkan.
type: docs
weight: 118
url: /id/aspose.slides/background/geteffective/
---
## Background::GetEffective() method


Mendapatkan data latar belakang yang efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Nilai Kembali

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Catatan



Contoh ini menunjukkan cara mendapatkan properti latar belakang yang efektif. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Kelas [Background](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)