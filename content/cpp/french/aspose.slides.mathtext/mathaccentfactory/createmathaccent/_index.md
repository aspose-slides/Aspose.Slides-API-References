---
title: CreateMathAccent()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) method

Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer l'accent |

### Valeur de retour

nouvel accent mathématique

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) method

Crée un accent mathématique appliqué à un élément mathématique spécifié

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer l'accent |
| accentCharacter | char16_t | caractère d'accent |

### Valeur de retour

nouvel accent mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathAccentFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)