---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the ink effect type (e.g., Galaxy, Gold, Silver) that defines the visual style of the ink stroke. The value is parsed from the brush property \"inkEffects\". If no recognized effect is specified, InkEffectType::NotDefined is returned."
type: docs
weight: 53
url: /aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() method


Gets the ink effect type (e.g., Galaxy, Gold, Silver) that defines the visual style of the ink stroke. The value is parsed from the brush property \"inkEffects\". If no recognized effect is specified, [InkEffectType::NotDefined](../../inkeffecttype/) is returned.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## See Also

* Enum [InkEffectType](../../inkeffecttype/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)