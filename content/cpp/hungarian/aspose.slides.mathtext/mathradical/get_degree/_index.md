---
title: get_Degree()
second_title: Aspose.Slides C++ API referencia
description: Degree argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metódus


Degree argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Megjegyzések


Példa: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathRadical](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)