---
title: Function()
second_title: Riferimento API di Aspose.Slides per C++
description: Accetta una funzione di un argomento usando questa istanza come nome della funzione
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metodo

Prende una funzione di un argomento usando questa istanza come nome della funzione

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un argomento della funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metodo

Prende una funzione di un argomento usando questa istanza come nome della funzione

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Un argomento della funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)