---
title: get_HideBottom()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() méthode

Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```
## Remarques

Exemple:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```
## Voir aussi

* Classe [IMathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)