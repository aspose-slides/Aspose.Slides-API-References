---
title: set_IsDecorative()
second_title: Référence API Aspose.Slides pour C++
description: Définit l'option 'Mark as decorative' en lecture/écriture bool.
type: docs
weight: 417
url: /fr/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) méthode

Définit l'option 'Mark as decorative' en lecture/écriture **bool**.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
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