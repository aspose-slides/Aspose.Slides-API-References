---
title: InsertColumnAfter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.
type: docs
weight: 326
url: /fr/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) méthode


Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index de la colonne après laquelle insérer une nouvelle |
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)