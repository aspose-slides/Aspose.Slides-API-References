---
title: get_Name()
second_title: Aspose.Slides C++ API hivatkozás
description: Függvény neve Például a függvénynevek a sin és a cos
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() metódus

Függvény neve Például a függvénynevek a sin és a cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Megjegyzések

Példa:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathFunction](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)