---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API Referenciája
description: "A tinta hatás típusát (pl. Galaxy, Gold, Silver) adja vissza, amely meghatározza a tinta vonal vizuális stílusát. Az érték a brush tulajdonságból, a \"inkEffects\"-ből kerül beolvasásra. Ha nincs felismert hatás megadva, akkor InkEffectType::NotDefined kerül visszaadásra."
type: docs
weight: 53
url: /hu/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metódus

Lekérdezi a tinta hatás típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tinta vonal vizuális stílusát. Az érték a brush tulajdonságból, a \"inkEffects\"-ből kerül beolvasásra. Ha nincs felismert hatás megadva, akkor [InkEffectType::NotDefined](../../inkeffecttype/) kerül visszaadásra.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Megjegyzés

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Lásd még

* Enum [InkEffectType](../../inkeffecttype/)
* Osztály [IInkBrush](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)