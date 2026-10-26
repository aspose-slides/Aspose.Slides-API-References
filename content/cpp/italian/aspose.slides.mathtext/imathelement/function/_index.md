---
title: Function()
second_title: Riferimento API Aspose.Slides per C++
description: Accetta una funzione di un argomento utilizzando questa istanza come nome della funzione
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metodo


Prende una funzione di un argomento utilizzando questa istanza come nome della funzione

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Un argomento della funzione |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metodo


Prende una funzione di un argomento utilizzando questa istanza come nome della funzione

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Un argomento della funzione |

### Valore restituito

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
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)