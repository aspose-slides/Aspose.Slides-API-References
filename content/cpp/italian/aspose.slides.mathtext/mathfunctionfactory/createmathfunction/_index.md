---
title: CreateMathFunction()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea funzione matematica
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo


Crea funzione matematica

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valore di ritorno

nuova funzione matematica

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metodo


Crea funzione matematica

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valore di ritorno

nuova funzione matematica

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)