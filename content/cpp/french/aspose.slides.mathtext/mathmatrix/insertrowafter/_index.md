---
title: InsertRowAfter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.
type: docs
weight: 300
url: /fr/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) méthode

Insérer une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice de la ligne après laquelle insérer une nouvelle |
## Remarques



Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)