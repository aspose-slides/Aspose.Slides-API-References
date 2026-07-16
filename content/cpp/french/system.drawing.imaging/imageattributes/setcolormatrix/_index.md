---
title: SetColorMatrix()
second_title: Référence de l'API Aspose.Slides for C++
description: Définit la matrice d'ajustement des couleurs.
type: docs
weight: 183
url: /fr/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) méthode

Définit la matrice d'ajustement des couleurs.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | La matrice d'ajustement des couleurs à définir |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Spécifie le type d'image et de couleur qui seront affectés par la matrice d'ajustement des couleurs |
| type | [ColorAdjustType](../../coloradjusttype/) | Spécifie le type d'objets pour lequel la matrice d'ajustement des couleurs est définie |

## Voir aussi

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [ColorMatrix](../../colormatrix/)
* classe [ImageAttributes](../)
* espace de noms [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)