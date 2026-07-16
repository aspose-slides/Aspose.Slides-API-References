---
title: set_Character()
second_title: Référence API Aspose.Slides pour C++
description: "Caractère d'accent La valeur doit être comprise dans l'intervalle de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) méthode


Caractère d'accent La valeur doit être comprise dans l'intervalle de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valeur par défaut: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Remarques


Exemple:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Voir aussi

* Classe [MathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)