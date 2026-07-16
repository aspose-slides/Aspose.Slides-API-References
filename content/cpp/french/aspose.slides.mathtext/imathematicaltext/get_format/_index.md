---
title: get_Format()
second_title: Référence API Aspose.Slides pour C++
description: Propriétés de mise en forme du texte
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() méthode


Propriétés de mise en forme du texte

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
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
* Classe [IMathematicalText](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)