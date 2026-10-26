---
title: InsertRowBefore()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.
type: docs
weight: 287
url: /fr/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) méthode

Insère une nouvelle ligne avant celle spécifiée Initialement, tous les éléments de la nouvelle ligne sont null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice de la ligne avant laquelle insérer une nouvelle |
## Remarques



Exemple: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)