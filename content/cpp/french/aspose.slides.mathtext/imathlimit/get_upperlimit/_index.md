---
title: get_UpperLimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la limite supérieure ou inférieure
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() méthode


Spécifie la limite supérieure ou inférieure

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## Remarques


Exemple: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Voir aussi

* Classe [IMathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)