---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de effektiva formateringsdata för textramen med arv tillämpat.
type: docs
weight: 391
url: /sv/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metod

Hämtar de effektiva formateringsdata för textramen med arv tillämpat.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Returvärde

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Anmärkningar

Detta exempel demonstrerar hur man får några av de effektiva formateringsegenskaperna för textramen. 
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Klass [TextFrameFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)