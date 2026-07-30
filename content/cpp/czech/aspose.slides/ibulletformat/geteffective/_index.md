---
title: GetEffective()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Získá efektivní data formátování odrážek s aplikovaným děděním.
type: docs
weight: 248
url: /cs/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() metoda


Získá efektivní data formátování odrážek s aplikovaným děděním.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Návratová hodnota

Nějaký [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Poznámky



Tento příklad ukazuje, jak získat některé vlastnosti efektivního formátu odrážek. 
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Třída [IBulletFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)