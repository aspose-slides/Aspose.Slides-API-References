---
title: DeleteRow()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la ligne spécifiée
type: docs
weight: 300
url: /fr/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) méthode

Supprime la ligne spécifiée

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | L'index zéro de la ligne à supprimer. |
## Remarques



Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)