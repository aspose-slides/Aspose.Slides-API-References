---
title: CreateMathBar()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer une barre mathématique en l'appliquant à l'élément
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) méthode


Créer une barre mathématique en l'appliquant à l'élément

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la barre |

### Valeur de retour

nouvel élément de barre mathématique

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) méthode


Créer une barre mathématique en l'appliquant à l'élément

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la barre |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position de la barre |

### Valeur de retour

nouvel élément de barre mathématique

## Voir aussi

* Énumération [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBar](../../imathbar/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBarFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)