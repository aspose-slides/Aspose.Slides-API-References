---
title: Function()
second_title: Référence de l'API Aspose.Slides pour C++
description: Prend une fonction d'un argument en utilisant cette instance comme nom de fonction
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) méthode

Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Un argument de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) méthode


Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Un argument de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [IMathFunction](../../imathfunction/)
## Remarques



Exemple: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)