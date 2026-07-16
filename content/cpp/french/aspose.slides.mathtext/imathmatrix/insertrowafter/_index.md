---
title: InsertRowAfter()
second_title: Référence API Aspose.Slides pour C++
description: Insère une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.
type: docs
weight: 287
url: /fr/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) méthode


Insère une nouvelle ligne après celle spécifiée. Au départ, tous les éléments de la nouvelle ligne sont nuls.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Index de la ligne après laquelle insérer une nouvelle |
## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)