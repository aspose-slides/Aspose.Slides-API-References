---
title: SetColorMatrix()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la matriz de ajuste de color.
type: docs
weight: 183
url: /es/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) method


Establece la matriz de ajuste de color.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | La matriz de ajuste de color a establecer |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Especifica el tipo de imagen y color que serán afectados por la matriz de ajuste de color |
| type | [ColorAdjustType](../../coloradjusttype/) | Especifica el tipo de objetos para los que se establece la matriz de ajuste de color |

## Ver también

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ColorMatrix](../../colormatrix/)
* Clase [ImageAttributes](../)
* Espacio de nombres [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)