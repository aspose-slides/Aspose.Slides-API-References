---
title: get_InkEffect()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visivo del tratto d'inchiostro. Il valore viene analizzato dalla proprietà del pennello \"inkEffects\". Se non viene specificato alcun effetto riconosciuto, InkEffectType::NotDefined viene restituito."
type: docs
weight: 53
url: /it/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metodo


Restituisce il tipo di effetto inchiostro (ad es., Galaxy, Gold, Silver) che definisce lo stile visivo del tratto d'inchiostro. Il valore viene analizzato dalla proprietà del pennello "inkEffects". Se non viene specificato alcun effetto riconosciuto, [InkEffectType::NotDefined](../../inkeffecttype/) viene restituito.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Vedi anche

* Enum [InkEffectType](../../inkeffecttype/)
* Classe [IInkBrush](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)