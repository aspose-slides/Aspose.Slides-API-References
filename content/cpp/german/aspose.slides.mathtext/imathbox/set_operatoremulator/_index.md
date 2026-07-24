---
title: set_OperatorEmulator()
second_title: Aspose.Slides für C++ API-Referenz
description: "Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Trennpunkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie zum Beispiel '=='. Standardwert: false"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) Methode

Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Trennpunkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Hinweise

Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Siehe auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)