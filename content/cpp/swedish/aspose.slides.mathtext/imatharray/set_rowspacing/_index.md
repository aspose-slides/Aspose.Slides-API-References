---
title: set_RowSpacing()
second_title: Aspose.Slides för C++ API-referens
description: "Avstånd mellan rader i en matris Det används endast när RowSpacingRule är satt till 3 Exakt, i vilket fall måttenheten är punkter eller Multiple, i vilket fall måttenheten är halvlinjer. Default: 0"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metod


Avstånd mellan rader i en matris Den används endast när RowSpacingRule är satt till 3 Exakt, i vilket fall måttenheten är punkter eller Multiple, i vilket fall måttenheten är halvlinjer. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Anmärkningar


Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Se också

* Klass [IMathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)