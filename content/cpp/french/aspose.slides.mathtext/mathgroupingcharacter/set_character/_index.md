---
title: set_Character()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Caractère de regroupement Valeur par défaut: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) méthode

Caractère de regroupement Valeur par défaut: U+23DF (BOTTOM CURLY BRACKET)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
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