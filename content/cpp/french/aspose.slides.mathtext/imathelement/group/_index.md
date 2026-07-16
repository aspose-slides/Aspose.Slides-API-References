---
title: Group()
second_title: Référence de l'API Aspose.Slides for C++
description: Place cet élément dans un groupe en utilisant une accolade basse
type: docs
weight: 248
url: /fr/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() méthode

Place cet élément dans un groupe en utilisant une accolade basse

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### Valeur de retour

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarques



Exemple : 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) méthode

Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu’une accolade basse ou un autre

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| character | char16_t | Caractère de regroupement tel que ACCOLADE BASSE (U+23DF) ou tout autre |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position du caractère de regroupement |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base |

### Valeur de retour

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarques



Exemple : 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)