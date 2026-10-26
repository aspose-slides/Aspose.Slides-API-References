---
title: CreateMathFunction()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine mathematische Funktion
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode


Erstellt eine mathematische Funktion

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element verwendet als Funktionsname |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element verwendet als Funktionsargument |

### Rückgabewert

neue mathematische Funktion

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) Methode


Erstellt eine mathematische Funktion

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Funktionsname |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element verwendet als Funktionsargument |

### Rückgabewert

neue mathematische Funktion

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFunctionFactory](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)