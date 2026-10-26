---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan data format garis yang efektif dengan penerapan pewarisan.
type: docs
weight: 417
url: /id/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metode


Mendapatkan data format garis yang efektif dengan penerapan pewarisan.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Nilai Kembalian

Sebuah [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Keterangan



Contoh ini mendemonstrasikan cara mengambil properti format garis efektif dari bentuk.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Kelas [LineFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)