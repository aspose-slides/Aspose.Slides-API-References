---
title: get_OperatorEmulator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Émulateur d'opérateur. Lorsque la valeur est vraie, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsqu'un ou plusieurs glyphes se combinent pour former un opérateur, tel que « == ». Valeur par défaut : false"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() méthode


Émulateur d'opérateur. Lorsque la valeur est vraie, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un saut de ligne et peut être aligné avec d’autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsqu’un ou plusieurs glyphes se combinent pour former un opérateur, comme « == ». Valeur par défaut : false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Remarques


Exemple :
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Voir aussi

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)