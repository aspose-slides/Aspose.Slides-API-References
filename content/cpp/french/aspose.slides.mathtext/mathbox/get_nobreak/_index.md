---
title: get_NoBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Pas de rupture Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsqu'elle est vraie, aucune rupture de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() méthode

No break Cette propriété spécifie la propriété \"unbreakable\" de la boîte d'objet. Lorsqu'elle est vraie, aucune rupture de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
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