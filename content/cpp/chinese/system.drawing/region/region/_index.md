---
title: Region()
second_title: Aspose.Slides C++ API 参考
description: 构造 Region 类的新实例。
type: docs
weight: 1
url: /zh/system.drawing/region/region/
---
## Region::Region() 构造函数

构造一个 [Region](../) 类的实例。

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) 构造函数

构造一个 [Region](../) 类的实例，该实例表示由指定矩形定义的区域。

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定义区域的矩形 |

## Region::Region(const Rectangle\&) 构造函数

构造一个 [Region](../) 类的实例，该实例表示由指定矩形定义的区域。

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定义区域的矩形 |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 构造函数

构造一个 [Region](../) 类的实例，该实例表示由指定路径定义的区域。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定义区域的路径 |

## Region::Region(const SkPath\&) 构造函数

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) 构造函数

构造一个 [Region](../) 类的实例，该实例表示由指定 RegionData 对象定义的区域。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | 定义区域的 RegionData 对象 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Region](../)
* 类 [RectangleF](../../rectanglef/)
* 类 [Rectangle](../../rectangle/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 类 [RegionData](../../../system.drawing.drawing2d/regiondata/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)