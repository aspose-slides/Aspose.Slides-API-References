---
title: set_SeparatorCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le caractère séparateur de délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut: '|'."
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) méthode


Le caractère séparateur de délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Remarques


Exemple :
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)