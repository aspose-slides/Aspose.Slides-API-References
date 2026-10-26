---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv punktsformateringsdata med arv tillämpat.
type: docs
weight: 248
url: /sv/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() metod

Hämtar effektiv punktsformateringsdata med arv tillämpat.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### Returvärde

Ett [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).

## Anmärkningar

Detta exempel visar hur man hämtar några effektiva punktsformatsegenskaper.
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

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Klass [IBulletFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)