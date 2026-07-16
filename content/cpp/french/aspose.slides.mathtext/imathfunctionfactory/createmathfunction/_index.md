---
title: CreateMathFunction()
second_title: Référence API Aspose.Slides pour C++
description: Crée une fonction mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode

Crée une fonction mathématique

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valeur de retour

nouvelle fonction mathématique

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) méthode

Crée une fonction mathématique

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Valeur de retour

nouvelle fonction mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)