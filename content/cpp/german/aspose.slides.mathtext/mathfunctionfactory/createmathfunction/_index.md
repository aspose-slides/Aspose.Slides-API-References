---
title: CreateMathFunction()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine mathematische Funktion
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode


Erstellt eine mathematische Funktion

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element, das als Funktionsname verwendet wird |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element, das als Funktionsargument verwendet wird |

### Rückgabewert

neue mathematische Funktion

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) Methode


Erstellt eine mathematische Funktion

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Funktionsname |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element, das als Funktionsargument verwendet wird |

### Rückgabewert

neue mathematische Funktion

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunctionFactory](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)