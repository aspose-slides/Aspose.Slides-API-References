---
title: get_RowSpacing()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Mezera mezi řádky pole Používá se pouze když je RowSpacingRule nastaveno na 3. Přesně v tomto případě je jednotkou míry body nebo Multiple, v tomto případě je jednotkou míry půlřádky. Výchozí: 0"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metoda


Mezera mezi řádky pole Používá se pouze když je RowSpacingRule nastaveno na 3. Přesně v tomto případě je jednotkou míry body nebo Multiple, v tomto případě je jednotkou míry půlřádky. Výchozí: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Viz také

* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)