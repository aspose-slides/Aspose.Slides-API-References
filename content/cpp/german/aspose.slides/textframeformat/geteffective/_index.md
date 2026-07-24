---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt wirksame Textframe-Formatierungsdaten mit angewandter Vererbung.
type: docs
weight: 391
url: /de/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() Methode

Ermittelt die wirksamen Textframe-Formatierungsdaten mit angewandter Vererbung.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Rückgabewert

Ein [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Anmerkungen


Dieses Beispiel zeigt, wie einige wirksame Textframe-Formatierungseigenschaften abgerufen werden.
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Klasse [TextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)