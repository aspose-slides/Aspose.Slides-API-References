---
title: MathFunction()
second_title: Aspose.Slides för C++ API-referens
description: Initialiserar en ny instans av MathFunction-klassen.
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor

Initierar en ny instans av klassen [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Anmärkningar

Exempel:
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) konstruktor

Initierar en ny instans av klassen [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Anmärkningar

Exempel:
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathFunction](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)