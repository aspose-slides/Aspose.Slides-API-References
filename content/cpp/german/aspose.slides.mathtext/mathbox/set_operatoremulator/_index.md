---
title: set_OperatorEmulator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Hinweis für einen Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann. Operator Emulators werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, z. B. '=='. Standardwert: false"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) Methode


Operator Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Hinweis für einen Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann. Operator Emulators werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, z. B. '=='. Standardwert: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Bemerkungen


Beispiel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)