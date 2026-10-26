---
title: CreateMathFunction()
second_title: Aspose.Slides C++ API hivatkozás
description: Matematikai függvényt hoz létre
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus

Létrehoz egy matematikai függvényt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az elem, amely a függvény nevéhez használatos |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az elem, amely a függvény argumentumaként használatos |

### Visszatérési érték

új matematikai függvény

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metódus

Létrehoz egy matematikai függvényt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Függvény neve |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az elem, amely a függvény argumentumaként használatos |

### Visszatérési érték

új matematikai függvény

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFunction](../../imathfunction/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathFunctionFactory](../)
* Osztály [String](../../../system/string/)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)