---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ Riferimento API
description: "Specifica l'allineamento dell'array rispetto al testo circostante. Il testo al di fuori dell'array può essere allineato con la parte inferiore, superiore o al centro di un oggetto array. Valore predefinito: Center"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metodo


Specifica l'allineamento dell'array rispetto al testo circostante. Il testo al di fuori dell'array può essere allineato con la parte inferiore, superiore o al centro di un oggetto array. Valore predefinito: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Osservazioni


Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Vedi anche

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)