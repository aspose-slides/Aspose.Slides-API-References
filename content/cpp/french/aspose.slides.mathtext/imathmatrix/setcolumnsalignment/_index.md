---
title: SetColumnsAlignment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'alignement horizontal des colonnes spécifiées
type: docs
weight: 261
url: /fr/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) méthode

Définit l'alignement horizontal des colonnes spécifiées

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice basé sur zéro de la première colonne dont l'alignement doit être défini |
| columnsCount | **uint32_t** | Nombre de colonnes pour spécifier l'alignement |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |
## Remarques



Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Voir aussi

* Énumération [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)