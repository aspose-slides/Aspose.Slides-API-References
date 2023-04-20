---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective text frame formatting data with the inheritance applied.
type: docs
weight: 391
url: /cpp/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() method


Gets effective text frame formatting data with the inheritance applied.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Return Value

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Remarks



This example demonstrates getting some of effective text frame formatting properties. 
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Class [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)