---
title: SetColorMatrix()
second_title: Aspose.Slides for C++ API Reference
description: Sets the color-adjustment matrix.
type: docs
weight: 183
url: /system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) method


Sets the color-adjustment matrix.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | The color-adjustment matrix to set |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Specifies the type of image and color that will be affected by the color-adjustment matrix |
| type | [ColorAdjustType](../../coloradjusttype/) | Specifies the type of objects for which the color-adjustment matrix is set |

## See Also

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)