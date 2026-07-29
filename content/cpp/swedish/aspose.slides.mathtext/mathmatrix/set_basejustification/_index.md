---
title: set_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom, och center. Standard: Center"
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) metod


Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Se även

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)