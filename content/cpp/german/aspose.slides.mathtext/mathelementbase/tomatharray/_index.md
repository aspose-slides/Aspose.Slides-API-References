---
title: ToMathArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt ein vertikales Array an
type: docs
weight: 170
url: /de/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() Methode


Legt ein vertikales Array an

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Rückgabewert

Neue Instanz des Typs [IMathArray](../../imatharray/)
## Bemerkungen



Beispiel: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathArray](../../imatharray/)
* Klasse [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)