---
title: GetEffective()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera skuteczne dane formatowania ramki tekstowej z uwzględnieniem dziedziczenia.
type: docs
weight: 391
url: /pl/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metoda


Pobiera skuteczne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Wartość zwracana

Obiekt [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie niektórych właściwości skutecznego formatowania ramki tekstowej. 
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

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Klasa [TextFrameFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)