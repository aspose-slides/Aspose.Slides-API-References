---
title: set_RowSpacing()
second_title: Aspose.Slides för C++ API-referens
description: "Mellanrum mellan rader i en matris Det används endast när RowSpacingRule är inställt på 3 Exakt i vilket fall måttenheten är punkter eller Multiple i vilket fall måttenheten är halvlinjer. Standard: 0"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metod


Mellanrum mellan rader i en matris Det används endast när RowSpacingRule är inställd på 3 Exakt i vilket fall måttenheten är punkter eller Multiple i vilket fall måttenheten är halvlinjer. Standard: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Anmärkningar


Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Se även

* Klass [MathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)