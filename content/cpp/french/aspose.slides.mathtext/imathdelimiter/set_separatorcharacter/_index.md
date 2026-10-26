---
title: set_SeparatorCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le caractère séparateur du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'."
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) méthode

Caractère séparateur du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut : '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
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