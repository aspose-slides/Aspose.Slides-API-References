---
title: DeleteColumn()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la colonne spécifiée
type: docs
weight: 339
url: /fr/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) méthode

Supprime la colonne spécifiée

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | L'index basé sur zéro de la colonne à supprimer. |
## Remarques



Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)