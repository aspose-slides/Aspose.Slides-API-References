---
title: get_UpperLimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la limite supérieure ou inférieure
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() méthode


Spécifie la limite supérieure ou inférieure

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Remarques


Exemple :
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Voir aussi

* Classe [MathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)