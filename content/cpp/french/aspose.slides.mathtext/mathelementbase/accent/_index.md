---
title: Accent()
second_title: Référence API Aspose.Slides pour C++
description: Définit un signe d'accent (un caractère au sommet de cet élément)
type: docs
weight: 196
url: /fr/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) méthode

Définit un signe d'accent (un caractère au sommet de cet élément)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| accentCharacter | char16_t | Caractère d'accent. La valeur doit être comprise dans la plage de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

### Valeur de retour

Nouvelle instance du type [IMathAccent](../../imathaccent/)

## Remarques

Exemple:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [MathElementBase](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)