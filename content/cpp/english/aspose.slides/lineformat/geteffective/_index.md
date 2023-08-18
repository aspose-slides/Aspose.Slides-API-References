---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective line formatting data with the inheritance applied.
type: docs
weight: 417
url: /aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() method


Gets effective line formatting data with the inheritance applied.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Return Value

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Remarks



This example demonstrates getting shape's effective line format properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Class [LineFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)