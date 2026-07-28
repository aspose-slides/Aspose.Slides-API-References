---
title: GetEffective()
second_title: Aspose.Slides for C++ API referencia
description: Lekérdezi a hatékony felsorolásformázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 248
url: /hu/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() módszer


Lekérdezi a hatékony felsorolásformázási adatokat az öröklődés alkalmazásával.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### Visszatérési érték

Egy [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja néhány hatékony felsorolásformátum tulajdonság lekérését. 
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

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Osztály [BulletFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)