---
title: ToBox()
second_title: Référence API Aspose.Slides pour C++
description: Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être groupé de façon à ne pas autoriser de sauts de ligne à l'intérieur.
type: docs
weight: 274
url: /fr/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() method

Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de saut de ligne, ou être groupé de manière à ne pas permettre de sauts de ligne à l’intérieur.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Valeur de retour

Boîte logique avec cet élément placé à l'intérieur

## Remarques

Exemple :
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)