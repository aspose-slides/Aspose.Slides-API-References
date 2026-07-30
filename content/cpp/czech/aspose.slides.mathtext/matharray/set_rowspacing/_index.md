---
title: set_RowSpacing()
second_title: Aspose.Slides pro C++ API Reference
description: "Rozestup mezi řádky pole. Používá se pouze tehdy, když je RowSpacingRule nastaven na 3, což znamená, že měrnou jednotkou jsou body, nebo na Multiple, kdy je měrnou jednotkou poloviční řádky. Výchozí: 0"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metoda

Rozestup mezi řádky pole. Používá se jen když je RowSpacingRule nastaven na 3, což znamená, že jednotkou jsou body, nebo Multiple, v tom případě je jednotkou poloviční řádky. Výchozí: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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