---
title: set_IsDecorative()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'option 'Marquer comme décoratif' en lecture/écriture bool.
type: docs
weight: 534
url: /fr/aspose.slides/shape/set_isdecorative/
---
## Shape::set_IsDecorative(bool) méthode


Définit l'option 'Mark as decorative' en lecture/écriture **bool**.

```cpp
void Aspose::Slides::Shape::set_IsDecorative(bool value) override
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