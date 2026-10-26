---
title: set_OperatorEmulator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateurs sont souvent utilisés lorsqu'un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : false"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) méthode

Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateurs sont souvent utilisés lorsqu'un ou plusieurs glyphes se combinent pour former un opérateur, comme '=='. Valeur par défaut : false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Remarques

Exemple : 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Voir aussi

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)