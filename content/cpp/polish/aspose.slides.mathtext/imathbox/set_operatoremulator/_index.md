---
title: set_OperatorEmulator()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Emulator operatora. Gdy wartość jest prawdziwa, pole i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt przerwania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub kilka glifów łączy się, tworząc operator, np. '=='. Domyślna wartość: false"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metoda


Emulator operatora. Gdy wartość jest prawdziwa, pole i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt przerwania linii i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub kilka glifów łączy się, tworząc operator, np. '=='. Domyślna wartość: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Zobacz także

* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)