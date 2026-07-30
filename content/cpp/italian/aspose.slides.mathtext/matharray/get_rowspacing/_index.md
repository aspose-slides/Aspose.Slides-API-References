---
title: get_RowSpacing()
second_title: Riferimento API Aspose.Slides per C++
description: "Spaziatura tra le righe di un array Viene usata solo quando RowSpacingRule è impostato a 3 Esattamente nel caso in cui l'unità di misura è punti o Multiple nel caso in cui l'unità di misura è mezze linee. Default: 0"
type: docs
weight: 118
url: /it/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metodo


Spaziatura tra le righe di un array Viene usata solo quando RowSpacingRule è impostato a 3 Esattamente nel caso in cui l'unità di misura è punti o Multiple nel caso in cui l'unità di misura è mezze linee. Predefinito: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Osservazioni


Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Vedi anche

* Classe [MathArray](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)