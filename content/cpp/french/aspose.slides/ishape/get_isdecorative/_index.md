---
title: get_IsDecorative()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'option 'Mark as decorative' lecture/écriture bool.
type: docs
weight: 404
url: /fr/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() méthode


Obtient l'option 'Mark as decorative' Lecture/écriture **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Voir aussi

* Classe [IShape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)