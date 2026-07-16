---
title: SetColumnsAlignment()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Définit l'alignement horizontal des colonnes spécifiées
type: docs
weight: 274
url: /fr/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) méthode

Définit l'alignement horizontal des colonnes spécifiées

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice de base zéro de la première colonne dont l'alignement doit être défini |
| columnsCount | **uint32_t** | Nombre de colonnes pour spécifier l'alignement |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |
## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Voir aussi

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)