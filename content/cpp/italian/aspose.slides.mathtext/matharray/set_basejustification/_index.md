---
title: set_BaseJustification()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. Valore predefinito: Center"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metodo

Specifica l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. Valore predefinito: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Osservazioni

Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Vedi anche

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)