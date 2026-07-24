---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt wirksame Aufzählungsformatierungsdaten, bei denen die Vererbung angewendet wurde.
type: docs
weight: 248
url: /de/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() Methode


Ermittelt wirksame Aufzählungsformatierungsdaten, bei denen die Vererbung angewendet wurde.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### Rückgabewert

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Hinweise



Dieses Beispiel demonstriert das Abrufen einiger wirksamer Aufzählungsformateigenschaften. 
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Klasse [BulletFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)