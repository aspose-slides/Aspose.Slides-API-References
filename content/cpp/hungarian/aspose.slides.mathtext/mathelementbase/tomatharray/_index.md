---
title: ToMathArray()
second_title: Aspose.Slides C++ API referencia
description: Függőleges tömbbe helyezi
type: docs
weight: 170
url: /hu/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metódus


Függőleges tömbbe helyezi

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Visszatérési érték

Az [IMathArray](../../imatharray/) típusú új példány
## Megjegyzések



Példa: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathArray](../../imatharray/)
* Osztály [MathElementBase](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)