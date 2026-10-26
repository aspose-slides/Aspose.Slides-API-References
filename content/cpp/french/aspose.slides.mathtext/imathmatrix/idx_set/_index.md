---
title: idx_set()
second_title: Référence de l'API Aspose.Slides pour C++
description: Éléments de la matrice
type: docs
weight: 222
url: /fr/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) méthode

Éléments de la matrice

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| row | **int32_t** | L'index basé sur zéro de la ligne pour obtenir l'élément |
| column | **int32_t** | L'index basé sur zéro de la colonne pour obtenir l'élément |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

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