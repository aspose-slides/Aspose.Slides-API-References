---
title: get_RowSpacing()
second_title: Riferimento API Aspose.Slides per C++
description: "Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel caso in cui l'unità di misura è punti o Multiple, nel caso in cui l'unità di misura è mezze linee. Predefinito: 0"
type: docs
weight: 118
url: /it/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metodo

Spaziatura tra le righe di un array Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti o Multiple, nel qual caso l'unità di misura è mezze linee. Predefinito: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
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