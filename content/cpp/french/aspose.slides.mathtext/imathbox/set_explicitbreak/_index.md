---
title: set_ExplicitBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le saut explicite indique s'il y a un retour à la ligne au début de l'objet Box, de sorte que la ligne s'enroule au début de l'objet box. Il indique le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) méthode

Saut explicite indique s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne s'enroule au début de l'objet Box. Indique le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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