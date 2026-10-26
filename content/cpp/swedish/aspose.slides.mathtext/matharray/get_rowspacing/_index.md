---
title: get_RowSpacing()
second_title: Aspose.Slides för C++ API-referens
description: "Mellanrum mellan rader i en matris Den används endast när RowSpacingRule är inställt på 3 Exactly, där måttenheten är punkter eller Multiple, där måttenheten är halva rader. Standard: 0"
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metod


Mellanrum mellan rader i en matris. Den används endast när RowSpacingRule är inställt på 3 Exactly, där måttenheten är punkter eller på Multiple, där måttenheten är halva rader. Standard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
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