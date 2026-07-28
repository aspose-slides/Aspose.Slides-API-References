---
title: CreateMathFunction()
second_title: Aspose.Slides C++ API Referencia
description: Létrehozza a matematikai függvényt
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Létrehozza a matematikai függvényt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elem, amely a függvény névként szolgál |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elem, amely a függvény argumentumaként szolgál |

### Visszatérési érték

új matematikai függvény

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method

Létrehozza a matematikai függvényt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Függvény neve |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elem, amely a függvény argumentumaként szolgál |

### Visszatérési érték

új matematikai függvény

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFunction](../../imathfunction/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathFunctionFactory](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)