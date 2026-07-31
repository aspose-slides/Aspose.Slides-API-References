---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan data pemformatan bagian yang efektif dengan penerapan pewarisan.
type: docs
weight: 131
url: /id/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metode

Mendapatkan data pemformatan bagian yang efektif dengan penerapan pewarisan.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Nilai Kembalian

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Catatan

Contoh ini menunjukkan cara mendapatkan beberapa properti format bagian yang efektif. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Kelas [PortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)