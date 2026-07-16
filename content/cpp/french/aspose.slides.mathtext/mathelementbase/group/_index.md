---
title: Group()
second_title: Référence API Aspose.Slides pour C++
description: Place cet élément dans un groupe en utilisant une accolade fermante
type: docs
weight: 235
url: /fr/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() méthode

Place cet élément dans un groupe en utilisant une accolade fermante

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### Valeur de retour

Nouvelle instance du type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarques



Exemple : 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) méthode

Place cet élément dans un groupe en utilisant un caractère de regroupement tel que l’accolade fermante ou un autre

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| character | char16_t | Caractère de regroupement tel que BOTTOM CURLY BRACKET (U+23DF) ou tout autre |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position du caractère de regroupement |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top signifie que le haut de l'objet tombe sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base |

### Valeur de retour

Nouvelle instance du type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarques



Exemple : 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [MathElementBase](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)