---
title: InsertRowBefore()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insérez une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.
type: docs
weight: 274
url: /fr/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) méthode

Insérez une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Indice de la ligne avant laquelle insérer une nouvelle |

## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)