---
title: set_NoBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Pas de saut. Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsque true, aucun saut de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comportent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des sauts peuvent se produire à l'intérieur de la boîte. Valeur par défaut: true"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) méthode

Pas de saut. Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsque true, aucun saut de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des sauts peuvent se produire à l'intérieur de la boîte. Valeur par défaut: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Remarques

Exemple :
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)