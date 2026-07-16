---
title: get_EndingCharacter()
second_title: Référence API Aspose.Slides pour C++
description: "Le caractère de fin de délimiteur spécifie le caractère de délimiteur de clôture ou de terminaison. Les délimiteurs mathématiques sont des caractères d'encapsulation tels que les parenthèses, les crochets et les accolades. La valeur par défaut : ')'."
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() méthode

Le caractère de fin de délimiteur spécifie le caractère de délimiteur de clôture ou de terminaison. Les délimiteurs mathématiques sont des caractères d’encapsulation tels que les parenthèses, les crochets et les accolades. La valeur par défaut: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Remarques

Exemple:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)