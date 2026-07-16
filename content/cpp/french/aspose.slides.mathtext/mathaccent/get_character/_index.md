---
title: get_Character()
second_title: Référence API Aspose.Slides pour C++
description: "Caractère d'accent La valeur doit être comprise dans la plage de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() méthode


Caractère d'accent La valeur doit être comprise dans la plage de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valeur par défaut: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Remarques


Exemple : 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Voir aussi

* Classe [MathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)