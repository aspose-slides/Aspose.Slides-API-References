---
title: get_BaseJustification()
second_title: Aspose.Slides voor C++ API Referentie
description: "Specificeert de verticale uitlijning ten opzichte van de omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center"
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() methode

Specificeert de verticale uitlijning ten opzichte van de omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Zie ook

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)