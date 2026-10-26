---
title: CreateMathGroupingCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un caractère de groupement mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) méthode

Crée un caractère de groupement mathématique

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |
| character | char16_t | grouping character |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertical justification |

### Valeur de retour

nouvel élément de caractère de groupement

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) méthode

Crée un caractère de groupement mathématique

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |

### Valeur de retour

nouvel élément de caractère de groupement

## Voir aussi

* Énum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathGroupingCharacterFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)