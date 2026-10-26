---
title: set_RowSpacing()
second_title: Aspose.Slides per C++ Riferimento API
description: "Spaziatura tra le righe di un array. Viene utilizzata solo quando RowSpacingRule è impostata a 3 esattamente, nel qual caso l'unità di misura è punti, o Multiple, nel qual caso l'unità di misura è mezze linee. Predefinito: 0"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metodo

Spaziatura tra le righe di un array Viene utilizzata solo quando RowSpacingRule è impostata a 3 Esattamente in tal caso l'unità di misura è punti o Multiple in tal caso l'unità di misura è mezze linee. Predefinito: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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
* Library [Aspose.Slides](../../../)