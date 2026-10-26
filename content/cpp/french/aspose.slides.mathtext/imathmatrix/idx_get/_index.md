---
title: idx_get()
second_title: Référence API Aspose.Slides pour C++
description: Éléments de la matrice
type: docs
weight: 209
url: /fr/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) méthode

Éléments de la matrice

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| row | **int32_t** | L'indice basé sur zéro de la ligne pour obtenir l'élément |
| column | **int32_t** | L'indice basé sur zéro de la colonne pour obtenir l'élément |

### Valeur de retour


## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)