---
title: ToMathArray()
second_title: Aspose.Slides für C++ API Referenz
description: Setzt Kindelemente in ein vertikales Array
type: docs
weight: 235
url: /de/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() Methode


Setzt Kindelemente in ein vertikales Array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Rückgabewert

Neue Instanz des Typs [IMathArray](../../imatharray/)
## Hinweise



Beispiel: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathArray](../../imatharray/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)