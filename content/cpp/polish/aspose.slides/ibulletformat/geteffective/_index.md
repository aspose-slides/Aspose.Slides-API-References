---
title: GetEffective()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera efektywne dane formatowania wypunktowania z zastosowanym dziedziczeniem.
type: docs
weight: 248
url: /pl/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() metoda


Pobiera efektywne dane formatowania wypunktowania z zastosowanym dziedziczeniem.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Wartość zwracana

Obiekt [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie niektórych efektywnych właściwości formatowania wypunktowania.
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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Klasa [IBulletFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)