---
title: get_InkEffect()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het type ink-effect op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreek bepaalt. De waarde wordt geparseerd uit de brush-eigenschap \"inkEffects\". Als er geen herkend effect is opgegeven, wordt InkEffectType::NotDefined geretourneerd."
type: docs
weight: 53
url: /nl/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() methode

Haalt het type inkt-effect op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreek bepaalt. De waarde wordt geparseerd uit de brush-eigenschap "inkEffects". Als er geen herkend effect is opgegeven, wordt [InkEffectType::NotDefined](../../inkeffecttype/) geretourneerd.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Zie ook

* Enumeratie [InkEffectType](../../inkeffecttype/)
* Klasse [IInkBrush](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Bibliotheek [Aspose.Slides](../../../)