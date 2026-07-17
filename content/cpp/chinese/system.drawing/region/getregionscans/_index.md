---
title: GetRegionScans()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 RectangleF 结构数组，在应用指定的矩阵变换后近似此 Region。
type: docs
weight: 27
url: /zh/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const 方法

返回一个 [RectangleF](../../rectanglef/) 结构数组，该数组在应用指定的矩阵变换后近似此 [Region](../)。

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 表示要应用于区域的几何变换的 Matrix。 |

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 类 [Region](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)