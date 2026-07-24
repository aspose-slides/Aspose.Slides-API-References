---
title: get_InkEffect()
second_title: Aspose.Slides für C++ API Referenz
description: "Ermittelt den Tinteneffekt-Typ (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenstrichs definiert. Der Wert wird aus der brush property \"inkEffects\" geparst. Wenn kein erkannter Effekt angegeben ist, wird InkEffectType::NotDefined zurückgegeben."
type: docs
weight: 53
url: /de/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() Methode

Ermittelt den Tinteneffekt-Typ (z. B. Galaxy, Gold, Silver), der den visuellen Stil des Tintenstrichs definiert. Der Wert wird aus der brush property \"inkEffects\" geparst. Wenn kein erkannter Effekt angegeben ist, wird [InkEffectType::NotDefined](../../inkeffecttype/) zurückgegeben.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Hinweise

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Siehe auch

* Enum [InkEffectType](../../inkeffecttype/)
* Klasse [IInkBrush](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)