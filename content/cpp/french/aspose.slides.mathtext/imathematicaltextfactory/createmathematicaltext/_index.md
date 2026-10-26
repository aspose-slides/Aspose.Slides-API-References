---
title: CreateMathematicalText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer un élément de texte mathématique vide
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() méthode

Créer un élément de texte mathématique vide

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```


### Valeur de retour

nouveau Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) méthode

Créer un élément de texte mathématique avec la valeur spécifiée

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | symbole unique à utiliser comme valeur de texte |

### Valeur de retour

nouveau Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) méthode

Créer un élément de texte mathématique vide avec la valeur spécifiée

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur de texte |

### Valeur de retour

nouveau Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) méthode

Créer un élément de texte mathématique vide avec la valeur spécifiée et les propriétés de formatage

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur de texte |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | paramètres de format du texte |

### Valeur de retour

nouveau Mathematical Text

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [IMathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)