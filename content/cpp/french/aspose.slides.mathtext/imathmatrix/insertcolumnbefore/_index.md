---
title: InsertColumnBefore()
second_title: Référence API Aspose.Slides pour C++
description: Insérez une nouvelle colonne avant celle spécifiée. Initialement tous les éléments de la nouvelle colonne sont null.
type: docs
weight: 313
url: /fr/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) méthode

Insérez une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice de la colonne avant laquelle insérer une nouvelle |
## Remarques



Exemple: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)