---
title: GetColumnAlignment()
second_title: Aspose.Slides pour C++ Référence API
description: Obtient l'alignement horizontal de la colonne spécifiée
type: docs
weight: 235
url: /fr/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) méthode


Obtenez l'alignement horizontal de la colonne spécifiée

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index de colonne basé sur zéro |

### Valeur de retour

Alignement horizontal de la colonne spécifiée
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Voir aussi

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)