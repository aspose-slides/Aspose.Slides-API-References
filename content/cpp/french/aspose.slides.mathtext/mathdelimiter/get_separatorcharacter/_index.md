---
title: get_SeparatorCharacter()
second_title: Référence API Aspose.Slides pour C++
description: "Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut : '|'."
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() méthode


Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut : '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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