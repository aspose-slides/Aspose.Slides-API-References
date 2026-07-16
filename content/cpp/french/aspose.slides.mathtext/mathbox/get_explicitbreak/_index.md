---
title: get_ExplicitBreak()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Explicit break indique s’il existe une rupture de ligne au début de l’objet Box, de sorte que la ligne se replie au début de l’objet box. Spécifie le numéro de l’opérateur sur la ligne précédente de texte mathématique qui doit être utilisé comme point d’alignement pour la ligne actuelle de texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)"
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() méthode


Explicit break spécifie s’il existe une rupture de ligne au début de l’objet Box, de sorte que la ligne se replie au début de l’objet box. Spécifie le numéro de l’opérateur sur la ligne précédente de texte mathématique qui doit être utilisé comme point d’alignement pour la ligne actuelle de texte mathématique. valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
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