---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de effectieve bulletopmaakgegevens op met de toegepaste overerving.
type: docs
weight: 248
url: /nl/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() methode


Haalt de effectieve bulletopmaakgegevens op met de toegepaste overerving.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### Retourwaarde

Een [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Opmerkingen



Dit voorbeeld toont hoe enkele effectieve bulletopmaak-eigenschappen worden opgehaald. 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Klasse [BulletFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)