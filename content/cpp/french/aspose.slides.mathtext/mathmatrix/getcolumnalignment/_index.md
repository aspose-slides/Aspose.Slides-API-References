---
title: GetColumnAlignment()
second_title: Référence API Aspose.Slides pour C++
description: Obtient l'alignement horizontal de la colonne spécifiée
type: docs
weight: 248
url: /fr/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) method

Obtient l'alignement horizontal de la colonne spécifiée

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice de colonne à base zéro |

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
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)