---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective portion formatting data with the inheritance applied.
type: docs
weight: 131
url: /aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() method


Gets effective portion formatting data with the inheritance applied.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Return Value

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Remarks



This example demonstrates getting some effective portion format properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Class [PortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)