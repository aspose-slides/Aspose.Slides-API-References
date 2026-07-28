---
title: GetEffective()
second_title: Aspose.Slides C++ API referenciája
description: Lekéri a tényleges felsorolásformázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 248
url: /hu/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() metódus

Lekéri a tényleges felsorolásformázási adatokat az öröklődés alkalmazásával.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### Visszatérési érték

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).

## Megjegyzés

Ez a példa bemutatja, hogyan lehet lekérni néhány tényleges felsorolásformátum-tulajdonságot.
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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Osztály [IBulletFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)