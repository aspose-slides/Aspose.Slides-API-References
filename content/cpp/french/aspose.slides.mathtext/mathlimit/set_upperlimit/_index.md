---
title: set_UpperLimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la limite supérieure ou inférieure
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) méthode

Spécifie la limite supérieure ou inférieure

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## Remarques

Exemple:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Voir aussi

* Classe [MathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)