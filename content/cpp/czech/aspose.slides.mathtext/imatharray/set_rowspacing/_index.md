---
title: set_RowSpacing()
second_title: Aspose.Slides pro C++ API Reference
description: "Rozestup mezi řádky pole se používá pouze tehdy, když je RowSpacingRule nastaven na 3. Právě v tomto případě je jednotkou měření body nebo Multiple, v tomto případě je jednotkou měření půl-řádky. Výchozí: 0"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metoda


Rozestup mezi řádky pole se používá pouze tehdy, když je RowSpacingRule nastaven na 3. Přesně v tomto případě je jednotkou měření body nebo Multiple, v tomto případě je jednotkou měření půl-řádky. Výchozí: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Viz také

* Třída [IMathArray](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)