---
title: get_NoBreak()
second_title: Référence API Aspose.Slides for C++
description: "Pas de rupture. Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsque true, aucune coupure de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comprennent plus d'un opérateur binaire. Si cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() méthode

Pas de rupture. Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsque true, aucune coupure de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comprennent plus d'un opérateur binaire. Si cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
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