---
title: get_InkEffect()
second_title: Aspose.Slides dla C++ API Reference
description: "Pobiera typ efektu tuszu (np. Galaxy, Gold, Silver), który definiuje wizualny styl pociągnięcia tuszu. Wartość jest parsowana z właściwości pędzla \"inkEffects\". Jeśli nie określono rozpoznanego efektu, InkEffectType::NotDefined jest zwracane."
type: docs
weight: 53
url: /pl/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metoda


Pobiera typ efektu tuszu (np. Galaxy, Gold, Silver), który definiuje wizualny styl pociągnięcia tuszu. Wartość jest parsowana z właściwości pędzla \"inkEffects\". Jeśli nie określono rozpoznanego efektu, [InkEffectType::NotDefined](../../inkeffecttype/) jest zwracane.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Zobacz także

* Enum [InkEffectType](../../inkeffecttype/)
* Klasa [IInkBrush](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)