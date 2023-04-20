---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective bullet formatting data with the inheritance applied.
type: docs
weight: 248
url: /cpp/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() method


Gets effective bullet formatting data with the inheritance applied.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Return Value

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Remarks



This example demonstrates getting some effective bullet format properties. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Class [IBulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)