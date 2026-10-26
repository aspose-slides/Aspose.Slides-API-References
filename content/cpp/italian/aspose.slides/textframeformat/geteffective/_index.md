---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera i dati di formattazione del frame di testo effettivi con l'ereditarietà applicata.
type: docs
weight: 391
url: /it/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metodo

Recupera i dati di formattazione del frame di testo effettivi con l'ereditarietà applicata.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Valore restituito

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## Osservazioni



Questo esempio mostra come ottenere alcune delle proprietà di formattazione del frame di testo effettive. 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Classe [TextFrameFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)