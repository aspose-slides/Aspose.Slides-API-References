---
title: set_EndingCharacter()
second_title: Référence API Aspose.Slides pour C++
description: "Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : ')'."
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) méthode


Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Remarques


Exemple : 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)