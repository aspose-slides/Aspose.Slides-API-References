---
title: AsArgumentOfFunction()
second_title: Aspose.Slides per C++ Riferimento API
description: Utilizza la funzione specificata usando questa istanza come argomento
type: docs
weight: 66
url: /it/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nome della funzione |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nome della funzione |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Uno dei tipi di funzione comuni a un argomento |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metodo


Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno dei tipi di funzione comuni a due argomenti: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Restituisce il logaritmo di 'x' alla base '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metodo


Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno dei tipi di funzione comuni a due argomenti: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore restituito

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Osservazioni



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Restituisce il logaritmo di 'x' alla base '5'
```

## Vedi anche

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)