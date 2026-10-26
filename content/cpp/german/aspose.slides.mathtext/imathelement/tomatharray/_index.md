---
title: ToMathArray()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt ein vertikales Array ein
type: docs
weight: 183
url: /de/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() Methode

Fügt ein vertikales Array ein

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### Rückgabewert

Neue Instanz vom Typ [IMathArray](../../imatharray/)
## Anmerkungen



Beispiel: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathArray](../../imatharray/)
* Klasse [IMathElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)