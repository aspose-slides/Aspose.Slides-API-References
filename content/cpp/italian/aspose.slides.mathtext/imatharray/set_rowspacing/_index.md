---
title: set_RowSpacing()
second_title: Riferimento API di Aspose.Slides per C++
description: "Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3, esattamente in questo caso l'unità di misura è punti o Multiple, in cui l'unità di misura è mezze linee. Predefinito: 0"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metodo

Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3, esattamente in questo caso l'unità di misura è punti o Multiple, in cui l'unità di misura è mezze linee. Predefinito: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Osservazioni

Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Vedi anche

* Classe [IMathArray](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)