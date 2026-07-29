---
title: get_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center"
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() metod


Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
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