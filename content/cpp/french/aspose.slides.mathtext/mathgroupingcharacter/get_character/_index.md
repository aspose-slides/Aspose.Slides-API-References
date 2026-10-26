---
title: get_Character()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Caractère de regroupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() méthode

Caractère de regroupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## Remarques

Exemple:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Parenthèse inférieure
```

## Voir aussi

* Classe [MathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)