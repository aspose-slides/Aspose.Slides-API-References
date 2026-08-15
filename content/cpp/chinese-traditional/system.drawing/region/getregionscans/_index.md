---
title: GetRegionScans()
second_title: Aspose.Slides C++ API 參考
description: 返回一個 RectangleF 結構的陣列，該陣列在套用指定的矩陣變換後近似此 Region。
type: docs
weight: 27
url: /zh-hant/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const 方法

返回一個 [RectangleF](../../rectanglef/) 結構的陣列，該陣列在套用指定的矩陣變換後近似此 [Region](../)。

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 表示要套用到區域的幾何變換的矩陣。 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 類別 [Region](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)