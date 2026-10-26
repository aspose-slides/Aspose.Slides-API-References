---
title: CreateMathFunction()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en matematisk funktion
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Skapar en matematisk funktion

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element som används som funktionsnamn |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element som används som funktionsargument |

### Returvärde

ny matematisk funktion

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method

Skapar en matematisk funktion

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Funktionsnamn |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element som används som funktionsargument |

### Returvärde

ny matematisk funktion

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFunction](../../imathfunction/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathFunctionFactory](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)