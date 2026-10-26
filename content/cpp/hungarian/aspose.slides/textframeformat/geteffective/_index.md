---
title: GetEffective()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri a hatékony szövegkeret formázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 391
url: /hu/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() metódus


Lekéri a hatékony szövegkeret formázási adatokat az öröklődés alkalmazásával.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Visszatérési érték

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Megjegyzés



Ez a példa bemutatja egyes hatékony szövegkeret formázási tulajdonságok lekérését. 
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

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Osztály [TextFrameFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)