---
title: ToMathArray()
second_title: Aspose.Slides C++ API referencia
description: A gyermekelemeket függőleges tömbbe helyezi
type: docs
weight: 235
url: /hu/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metódus


A gyermekelemeket függőleges tömbbe helyezi

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Visszatérési érték

Az [IMathArray](../../imatharray/) típusú új példány
## Megjegyzések



Példa: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathArray](../../imatharray/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)