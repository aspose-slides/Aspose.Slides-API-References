---
title: get_RowSpacing()
second_title: Aspose.Slides för C++ API-referens
description: "Mellanrum mellan rader i en array. Den används endast när RowSpacingRule är satt till 3 exakt, i vilket fall måttenheten är punkter eller Multiple, i vilket fall måttenheten är halvlinjer. Standard: 0"
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metod


Mellanrum mellan rader i en array Den används endast när RowSpacingRule är inställd på 3 Exakt i vilket fall måttenheten är punkter eller Multiple i vilket fall måttenheten är halvlinjer. Standard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Anmärkningar


Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Se även

* Klass [IMathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)