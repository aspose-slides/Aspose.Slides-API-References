---
title: SetColumnAlignment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'alignement horizontal de la colonne spécifiée
type: docs
weight: 261
url: /fr/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) méthode

Définit l'alignement horizontal de la colonne spécifiée

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index de colonne basé sur zéro |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Voir aussi

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)