---
title: set_Character()
second_title: Référence API Aspose.Slides pour C++
description: "Caractère de regroupement Valeur par défaut : U+23DF (ACCOLADE CROCHÉE INFÉRIEURE)"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) méthode


Valeur par défaut du caractère de regroupement: U+23DF (ACCOLADE CROCHÉE INFÉRIEURE)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Remarques


Exemple:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Parenthèse inférieure
```

## Voir aussi

* Classe [IMathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)