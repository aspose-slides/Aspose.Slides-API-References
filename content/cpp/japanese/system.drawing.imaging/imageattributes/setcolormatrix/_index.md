---
title: SetColorMatrix()
second_title: Aspose.Slides for C++ API リファレンス
description: 色調整行列を設定します。
type: docs
weight: 183
url: /ja/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) メソッド

色調整行列を設定します。

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | 設定する色調整行列 |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | カラー調整行列の影響を受ける画像と色のタイプを指定します |
| type | [ColorAdjustType](../../coloradjusttype/) | カラー調整行列が設定されるオブジェクトのタイプを指定します |

## 参照

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)