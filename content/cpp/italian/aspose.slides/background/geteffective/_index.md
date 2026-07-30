---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i dati di sfondo effettivi con l'eredità applicata.
type: docs
weight: 118
url: /it/aspose.slides/background/geteffective/
---
## Background::GetEffective() metodo

Ottiene i dati di sfondo effettivi con l'eredità applicata.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Valore restituito

Un [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## Osservazioni

Questo esempio dimostra come ottenere le proprietà di sfondo effettive.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Classe [Background](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)