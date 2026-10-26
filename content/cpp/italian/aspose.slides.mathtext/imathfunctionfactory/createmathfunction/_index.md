---
title: CreateMathFunction()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea funzione matematica
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo

Crea funzione matematica

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valore di ritorno

nuova funzione matematica

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metodo

Crea funzione matematica

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valore di ritorno

nuova funzione matematica

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)