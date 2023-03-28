---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective paragraph formatting data with the inheritance applied.
type: docs
weight: 365
url: /cpp/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() method


Gets effective paragraph formatting data with the inheritance applied.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Return Value

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Remarks



This example demonstrates getting some effective paragraph format properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Class [ParagraphFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
