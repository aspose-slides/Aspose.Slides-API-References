---
title: set_UpperLimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la limite supérieure ou inférieure
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) méthode

Spécifie la limite supérieure ou inférieure

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Remarques

Exemple :
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Voir aussi

* Classe [IMathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)