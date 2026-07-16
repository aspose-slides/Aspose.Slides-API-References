---
title: get_BeginningCharacter()
second_title: Référence API Aspose.Slides pour C++
description: "Le caractère de début du délimiteur spécifie le caractère de délimiteur d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. La valeur par défaut : '('."
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() méthode

Le caractère de début du délimiteur spécifie le caractère de délimiteur d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. La valeur par défaut : '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Remarques

Exemple :
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)