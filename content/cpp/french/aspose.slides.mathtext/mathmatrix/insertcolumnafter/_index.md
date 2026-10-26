---
title: InsertColumnAfter()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.
type: docs
weight: 339
url: /fr/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) méthode


Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index of the column after which to insert a new one |
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)