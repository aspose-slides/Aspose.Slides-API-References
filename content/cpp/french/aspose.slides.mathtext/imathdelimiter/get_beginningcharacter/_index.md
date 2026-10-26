---
title: get_BeginningCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le caractère de début du délimiteur indique le caractère de délimiteur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut: '('."
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() méthode

Le caractère de début du délimiteur indique le caractère de délimiteur de départ, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Remarques

Exemple :
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)