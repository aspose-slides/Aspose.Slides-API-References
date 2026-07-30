---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata.
type: docs
weight: 131
url: /it/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metodo

Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Valore di ritorno

Un [IPortionFormatEffectiveData](../../iportionformateffectivedata/).

## Osservazioni

Questo esempio dimostra come ottenere alcune proprietà del formato della porzione effettiva.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Classe [PortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)