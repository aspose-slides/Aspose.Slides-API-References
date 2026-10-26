---
title: DeleteRow()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la ligne spécifiée
type: docs
weight: 313
url: /fr/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) méthode

Supprime la ligne spécifiée

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | L'indice basé sur zéro de la ligne à supprimer. |
## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)