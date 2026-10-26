---
title: DeleteColumn()
second_title: Référence API Aspose.Slides pour C++
description: Supprime la colonne spécifiée
type: docs
weight: 352
url: /fr/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) méthode

Supprime la colonne spécifiée

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | L'indice basé sur zéro de la colonne à supprimer. |
## Remarques



Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)