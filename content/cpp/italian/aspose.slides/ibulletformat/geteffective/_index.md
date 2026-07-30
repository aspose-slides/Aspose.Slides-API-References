---
title: GetEffective()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera i dati di formattazione del punto elenco effettivi con l'ereditarietà applicata.
type: docs
weight: 248
url: /it/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() metodo


Ottiene i dati di formattazione dei punti elenco effettivi con l'ereditarietà applicata.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Valore di ritorno

Un [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Osservazioni



Questo esempio dimostra il recupero di alcune proprietà del formato dei punti elenco effettivo. 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Class [IBulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)