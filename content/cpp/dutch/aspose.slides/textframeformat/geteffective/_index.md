---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt effectieve tekstframe-opmaakgegevens op met de overerving toegepast.
type: docs
weight: 391
url: /nl/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() methode


Haalt de effectieve tekstframe-opmaakgegevens op met de overerving toegepast.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Retourwaarde

Een [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Opmerkingen



Dit voorbeeld laat zien hoe enkele effectieve tekstframe-opmaak eigenschappen worden opgehaald. 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Klasse [TextFrameFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)