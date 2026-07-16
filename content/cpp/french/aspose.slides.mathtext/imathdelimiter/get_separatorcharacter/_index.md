---
title: get_SeparatorCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut: '|'."
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() méthode


Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut : '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Remarques


Exemple :
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)