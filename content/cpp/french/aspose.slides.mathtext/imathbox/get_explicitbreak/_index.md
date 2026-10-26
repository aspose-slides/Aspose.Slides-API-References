---
title: get_ExplicitBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Saut explicite indique s'il y a un retour à la ligne au début de l'objet Box, de sorte que la ligne s'enroule au début de l'objet Box. Il indique le numéro de l'opérateur sur la ligne précédente de texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle de texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)"
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() méthode

Saut explicite indique s’il y a un retour à la ligne au début de l’objet Box, de sorte que la ligne s’enroule au début de l’objet Box. Il indique le numéro de l’opérateur sur la ligne précédente de texte mathématique qui doit être utilisé comme point d’alignement pour la ligne actuelle de texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Remarques

Exemple :
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)