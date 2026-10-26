---
title: set_BeginningCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le caractère de début du délimiteur indique le caractère délimiteur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : '('."
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) méthode

Le caractère de début du délimiteur indique le caractère délimitateur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Remarques

Exemple: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)