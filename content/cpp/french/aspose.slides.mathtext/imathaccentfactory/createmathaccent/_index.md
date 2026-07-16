---
title: CreateMathAccent()
second_title: Référence API Aspose.Slides pour C++
description: Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) méthode

Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d’accent par défaut

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer l’accent |

### Valeur de retour

nouvel accent mathématique

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) méthode

Crée un accent mathématique appliqué à un élément mathématique spécifié

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer l’accent |
| accentCharacter | char16_t | caractère d’accent |

### Valeur de retour

nouvel accent mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../../imathelement/)
* Class [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)