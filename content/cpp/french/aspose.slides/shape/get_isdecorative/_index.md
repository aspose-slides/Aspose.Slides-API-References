---
title: get_IsDecorative()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'option 'Mark as decorative' Lecture/écriture bool.
type: docs
weight: 521
url: /fr/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() méthode


Obtient l'option « Mark as decorative » Lecture/écriture **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Voir aussi

* Classe [Shape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)