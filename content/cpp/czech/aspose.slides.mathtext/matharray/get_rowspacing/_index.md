---
title: get_RowSpacing()
second_title: Aspose.Slides pro C++ API Reference
description: "Mezera mezi řádky pole. Používá se pouze, když je RowSpacingRule nastaven na 3. Exact, v tom případě je jednotkou měření body, nebo Multiple, v tom případě je jednotkou měření půlřádky. Výchozí: 0"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metoda


Mezera mezi řádky pole. Používá se pouze, když je RowSpacingRule nastaven na 3. Exact, v tom případě je jednotkou měření body, nebo Multiple, v tom případě je jednotkou měření půlřádky. Výchozí: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Viz také

* Třída [MathArray](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)