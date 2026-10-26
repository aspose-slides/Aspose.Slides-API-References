---
title: get_OperatorEmulator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Operator Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Trennstelle für einen Zeilenumbruch dienen kann und an anderen Operatoren ausgerichtet werden kann. Operator Emulators werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, zum Beispiel '=='. Standardwert: false"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() Methode

Operator Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Trennstelle für einen Zeilenumbruch dienen kann und an anderen Operatoren ausgerichtet werden kann. Operator Emulators werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, zum Beispiel '=='. Standardwert: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Hinweise

Beispiel:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)