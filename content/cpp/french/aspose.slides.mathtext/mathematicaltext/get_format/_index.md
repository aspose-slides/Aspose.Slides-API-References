---
title: get_Format()
second_title: Référence de l'API Aspose.Slides pour C++
description: Propriétés de formatage du texte
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() méthode


Propriétés de formatage du texte

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
```

## Remarques


Exemple :
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Classe [MathematicalText](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)