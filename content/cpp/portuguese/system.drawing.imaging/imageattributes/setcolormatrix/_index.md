---
title: SetColorMatrix()
second_title: Referência da API Aspose.Slides para C++
description: Define a matriz de ajuste de cor.
type: docs
weight: 183
url: /pt/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) método


Define a matriz de ajuste de cor.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | A matriz de ajuste de cor a ser definida |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Especifica o tipo de imagem e cor que será afetado pela matriz de ajuste de cor |
| type | [ColorAdjustType](../../coloradjusttype/) | Especifica o tipo de objetos para os quais a matriz de ajuste de cor é definida |

## Veja Também

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)