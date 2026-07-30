---
title: set_BaseJustification()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con la parte inferiore, la parte superiore o il centro di un oggetto array. Valore predefinito: Center"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) metodo


Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il bottom, il top o il center di un oggetto array. Valore predefinito: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Osservazioni


Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Vedi anche

* Enumerazione [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathArray](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)