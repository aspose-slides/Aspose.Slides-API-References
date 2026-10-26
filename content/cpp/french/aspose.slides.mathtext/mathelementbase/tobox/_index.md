---
title: ToBox()
second_title: Référence de l'API Aspose.Slides pour C++
description: Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encapsulé peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être regroupé de manière à ne pas autoriser de sauts de ligne à l'intérieur.
type: docs
weight: 261
url: /fr/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() méthode


Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique. Un objet encapsulé peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de saut de ligne, ou être regroupé de manière à ne pas autoriser de sauts de ligne à l’intérieur.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Valeur de retour

Boîte logique contenant cet élément
## Remarques



Exemple:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [MathElementBase](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)