---
title: InsertColumnBefore()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.
type: docs
weight: 326
url: /fr/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) méthode


Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice de la colonne avant laquelle insérer une nouvelle |
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)