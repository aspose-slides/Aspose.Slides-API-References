---
title: ToMathArray()
second_title: Aspose.Slides C++ API referencia
description: Függőleges tömbbe helyezi
type: docs
weight: 183
url: /hu/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metódus


Függőleges tömbbe helyezi

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### Visszatérési érték

New instance of type [IMathArray](../../imatharray/)
## Megjegyzések



Példa: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathArray](../../imatharray/)
* Osztály [IMathElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)