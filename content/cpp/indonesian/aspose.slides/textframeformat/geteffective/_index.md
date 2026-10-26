---
title: GetEffective()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan data format bingkai teks yang efektif dengan pewarisan yang diterapkan.
type: docs
weight: 391
url: /id/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metode


Mendapatkan data format bingkai teks yang efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Nilai Kembali

Sebuah [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Keterangan



Contoh ini menunjukkan cara mendapatkan beberapa properti format bingkai teks yang efektif. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Kelas [TextFrameFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)