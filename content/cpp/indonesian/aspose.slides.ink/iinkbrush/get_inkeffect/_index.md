---
title: get_InkEffect()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan tipe efek tinta (mis., Galaxy, Gold, Silver) yang menentukan gaya visual dari goresan tinta. Nilai diurai dari properti kuas \"inkEffects\". Jika tidak ada efek yang dikenali yang ditentukan, InkEffectType::NotDefined dikembalikan."
type: docs
weight: 53
url: /id/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() method

Mendapatkan tipe efek tinta (mis., Galaxy, Gold, Silver) yang menentukan gaya visual dari goresan tinta. Nilai diurai dari properti kuas \"inkEffects\". Jika tidak ada efek yang dikenali yang ditentukan, [InkEffectType::NotDefined](../../inkeffecttype/) dikembalikan.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Catatan

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Lihat Juga

* Enum [InkEffectType](../../inkeffecttype/)
* Kelas [IInkBrush](../)
* Ruang Nama [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)