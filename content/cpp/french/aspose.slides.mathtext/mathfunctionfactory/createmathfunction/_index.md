---
title: CreateMathFunction()
second_title: Référence API Aspose.Slides pour C++
description: Crée une fonction mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Crée une fonction mathématique

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Élément utilisé comme nom de fonction |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Élément utilisé comme argument de fonction |

### Valeur de retour

nouvelle fonction mathématique

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) méthode


Crée une fonction mathématique

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Nom de la fonction |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Élément utilisé comme argument de fonction |

### Valeur de retour

nouvelle fonction mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)