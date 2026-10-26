---
title: GetEffective()
second_title: Aspose.Slides pro C++ API Reference
description: Získá efektivní data formátování textového rámce s aplikovaným děděním.
type: docs
weight: 391
url: /cs/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metoda

Získá efektivní data formátování textového rámce s aplikovaným děděním.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Návratová hodnota

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Poznámky



Tento příklad ukazuje získání některých efektivních vlastností formátování textového rámce. 
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Třída [TextFrameFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)