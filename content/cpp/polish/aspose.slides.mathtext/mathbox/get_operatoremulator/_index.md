---
title: get_OperatorEmulator()
second_title: Aspose.Slides dla C++ - referencja API
description: "Emulator operatora. Gdy wartość jest prawdziwa, pole i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt przerwania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się, tworząc operator, taki jak '=='. Domyślna wartość: false"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metoda

Operator Emulator. Gdy wartość jest prawdziwa, pole i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt przerwania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się, tworząc operator, taki jak '=='. Domyślna wartość: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Uwagi

Przykład:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Zobacz także

* Klasa [MathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)