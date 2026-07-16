---
title: AsArgumentOfFunction()
second_title: Référence de l'API Aspose.Slides pour C++
description: Prend la fonction spécifiée en utilisant cette instance comme argument
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) method


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique du type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) method


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique du type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) method


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | L'un des types de fonction courants à un argument |

### Valeur de retour

Nouvel élément mathématique du type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) method


Utilise la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | L'un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument supplémentaire selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique du type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Retourne le logarithme de 'x' à la base '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) method


Utilise la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | L'un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argument supplémentaire selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique du type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Retourne le logarithme de 'x' à la base '5'
```

## Voir aussi

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)