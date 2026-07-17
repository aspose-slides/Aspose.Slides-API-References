---
title: SetColorMatrix()
second_title: Aspose.Slides for C++ API 参考
description: 设置颜色调整矩阵。
type: docs
weight: 183
url: /zh/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) 方法


设置颜色调整矩阵。

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | 要设置的颜色调整矩阵 |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | 指定将受到颜色调整矩阵影响的图像类型和颜色 |
| type | [ColorAdjustType](../../coloradjusttype/) | 指定为其设置颜色调整矩阵的对象类型 |

## 另请参见

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)