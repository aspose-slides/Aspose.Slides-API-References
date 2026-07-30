---
title: SetColorMatrix()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la matrice di regolazione del colore.
type: docs
weight: 183
url: /it/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) metodo


Imposta la matrice di regolazione del colore.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | La matrice di regolazione del colore da impostare |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Specifica il tipo di immagine e colore che sarà influenzato dalla matrice di regolazione del colore |
| type | [ColorAdjustType](../../coloradjusttype/) | Specifica il tipo di oggetti per i quali la matrice di regolazione del colore è impostata |

## Vedi anche

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)