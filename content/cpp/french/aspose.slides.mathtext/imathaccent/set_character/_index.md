---
title: set_Character()
second_title: Référence de l'API Aspose.Slides for C++
description: "Caractère d'accent La valeur doit être comprise dans la plage de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valeur par défaut : Accent circonflexe combiné (U+0302)"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) méthode

Caractère d'accent La valeur doit être comprise dans la plage de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valeur par défaut : Accent circonflexe combiné (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Remarques

Exemple :

```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Voir aussi

* Classe [IMathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)