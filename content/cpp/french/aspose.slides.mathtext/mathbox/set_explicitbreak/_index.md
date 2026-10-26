---
title: set_ExplicitBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Explicit break spécifie s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne s'enroule au début de l'objet Box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) méthode


Explicit break spécifie s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne s'enroule au début de l'objet Box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de saut explicite)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Remarques


Exemple : 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Voir aussi

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)