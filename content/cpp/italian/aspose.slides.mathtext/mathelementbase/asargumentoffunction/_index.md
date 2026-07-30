---
title: AsArgumentOfFunction()
second_title: Riferimento API Aspose.Slides per C++
description: Utilizza la funzione specificata usando questa istanza come argomento
type: docs
weight: 53
url: /it/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nome della funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Note



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nome della funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Note



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) metodo


Utilizza la funzione specificata usando questa istanza come argomento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Uno dei tipi di funzione comune a un argomento |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Note



Esempio: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metodo


Utilizza la funzione specificata usando questa istanza come argomento e l’argomento aggiuntivo specificato

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno dei tipi di funzione comune a due argomenti: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Note



Esempio: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Restituisce il logaritmo di 'x' alla base '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metodo


Utilizza la funzione specificata usando questa istanza come argomento e l’argomento aggiuntivo specificato

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno dei tipi di funzione comune a due argomenti: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathFunction](../../imathfunction/)
## Note



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
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)