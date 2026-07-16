---
title: set_NoBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Pas de rupture Cette propriété spécifie la propriété \"unbreakable\" sur la boîte d'objet. Lorsque la valeur est vraie, aucune coupure de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui se composent de plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des coupures peuvent survenir à l'intérieur de la boîte. Valeur par défaut : true"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) méthode

Pas de rupture Cette propriété spécifie la propriété \"unbreakable\" sur la boîte d'objet. Lorsque la valeur est vraie, aucune coupure de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui se composent de plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des coupures peuvent survenir à l'intérieur de la boîte. Valeur par défaut : true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Remarques


Exemple: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Voir aussi

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)