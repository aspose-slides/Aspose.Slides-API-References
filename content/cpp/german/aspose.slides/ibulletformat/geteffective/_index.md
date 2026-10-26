---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die wirksamen Aufzählungsformatdaten mit angewandter Vererbung.
type: docs
weight: 248
url: /de/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() Methode

Ermittelt die wirksamen Aufzählungsformatdaten mit angewandter Vererbung.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### Rückgabewert

Ein [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).

## Anmerkungen

Dieses Beispiel zeigt, wie einige wirksame Aufzählungsformat-Eigenschaften abgerufen werden.
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
* Klasse [IBulletFormat](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)