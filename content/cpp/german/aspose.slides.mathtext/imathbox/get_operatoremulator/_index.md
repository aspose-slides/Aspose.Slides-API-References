---
title: get_OperatorEmulator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als möglicher Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() Methode

Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als möglicher Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Anmerkungen

Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Siehe Auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)