---
title: SetColorMatrix()
second_title: Aspose.Slides for C++ API 參考
description: 設定顏色調整矩陣。
type: docs
weight: 183
url: /zh-hant/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) 方法

設定顏色調整矩陣。

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | 要設定的顏色調整矩陣 |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | 指定將受到顏色調整矩陣影響的影像與顏色類型 |
| type | [ColorAdjustType](../../coloradjusttype/) | 指定要設定顏色調整矩陣的物件類型 |

## 另請參閱

* 列舉 [ColorMatrixFlag](../../colormatrixflag/)
* 列舉 [ColorAdjustType](../../coloradjusttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ColorMatrix](../../colormatrix/)
* 類別 [ImageAttributes](../)
* 命名空間 [System::Drawing::Imaging](../../)
* 函式庫 [Aspose.Slides](../../../)