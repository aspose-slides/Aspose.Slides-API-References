---
title: get_OperatorEmulator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Émulateur d'opérateur. Lorsqu'il est vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un retour à la ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : false"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() méthode

Émulateur d'opérateur. Lorsqu'il est vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un retour à la ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Remarques

Exemple : 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)