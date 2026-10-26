---
title: MathFunction()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi sebuah instance baru dari kelas MathFunction.
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Menginisialisasi sebuah instance baru dari kelas [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Catatan


Contoh: 
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) constructor


Menginisialisasi sebuah instance baru dari kelas [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Catatan


Contoh: 
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathFunction](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)