---
title: set_OperatorEmulator()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : false"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) méthode

Émulateur d'opérateur. Lorsqu'il est vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Remarques

Exemple:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)