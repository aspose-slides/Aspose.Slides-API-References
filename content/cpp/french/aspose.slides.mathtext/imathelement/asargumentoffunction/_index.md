---
title: AsArgumentOfFunction()
second_title: Référence de l'API Aspose.Slides pour C++
description: Utilise la fonction spécifiée en utilisant cette instance comme argument
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) méthode


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) méthode


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) méthode


Utilise la fonction spécifiée en utilisant cette instance comme argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Un des types de fonction courants à un argument |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) méthode


Utilise la fonction spécifiée en utilisant cette instance comme argument et l’argument supplémentaire spécifié

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument supplémentaire selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Renvoie le logarithme de 'x' à la base '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) méthode


Utilise la fonction spécifiée en utilisant cette instance comme argument et l’argument supplémentaire spécifié

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argument supplémentaire selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple : 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Renvoie le logarithme de 'x' à la base '5'
```

## Voir aussi

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathFunction](../../imathfunction/)
* classe [IMathElement](../)
* classe [String](../../../system/string/)
* espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)