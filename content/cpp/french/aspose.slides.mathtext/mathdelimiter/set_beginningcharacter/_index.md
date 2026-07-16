---
title: set_BeginningCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le caractère de début du délimiteur spécifie le caractère de délimiteur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. La valeur par défaut : '('."
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) méthode

Le caractère de début du délimiteur spécifie le caractère de délimiteur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. La valeur par défaut : '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
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