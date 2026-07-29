---
title: get_InkEffect()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. Värdet läses från brush-egenskapen \"inkEffects\". Om ingen erkänd effekt anges, returneras InkEffectType::NotDefined."
type: docs
weight: 53
url: /sv/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metod

Hämtar bläckeffekttypen (t.ex. Galaxy, Gold, Silver) som definierar den visuella stilen för bläckstrecket. Värdet läses från brush-egenskapen \"inkEffects\". Om ingen erkänd effekt anges, returneras [InkEffectType::NotDefined](../../inkeffecttype/).

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Se även

* Enum [InkEffectType](../../inkeffecttype/)
* Klass [IInkBrush](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)