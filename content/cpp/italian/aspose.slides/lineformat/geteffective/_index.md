---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i dati di formattazione della linea effettiva con l'ereditarietà applicata.
type: docs
weight: 417
url: /it/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metodo

Ottiene i dati di formattazione della linea effettiva con l'ereditarietà applicata.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Valore di ritorno

Un [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Osservazioni


Questo esempio dimostra come ottenere le proprietà del formato della linea effettiva della forma. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Classe [LineFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)