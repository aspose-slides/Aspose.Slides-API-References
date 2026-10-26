---
title: set_EndingCharacter()
second_title: Référence API Aspose.Slides pour C++
description: "Le caractère de fin de délimiteur spécifie le caractère de délimiteur de fin, ou de fermeture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : ')'."
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) méthode


Le caractère de fin de délimiteur spécifie le caractère de délimiteur de fin, ou de fermeture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. La valeur par défaut : ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Remarques


Exemple : 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)