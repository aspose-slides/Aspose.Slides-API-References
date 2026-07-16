---
title: get_Character()
second_title: Référence API Aspose.Slides pour C++
description: "Caractère de regroupement Valeur par défaut: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() méthode

Caractère de regroupement Valeur par défaut: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
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