---
title: SetClip()
second_title: Aspose.Slides for C++ API 参考
description: 将当前 Graphics 对象表示的绘图表面的裁剪区域设置为指定操作的结果，该操作将当前裁剪区域与指定的区域合并。
type: docs
weight: 690
url: /zh/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) 方法

将当前 [Graphics](../) 对象表示的绘图表面的裁剪区域设置为指定操作的结果，该操作将当前裁剪区域与指定的区域合并。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 指定要合并的区域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定合并操作 |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) 方法


将当前 [Graphics](../) 对象表示的绘图表面的裁剪区域设置为指定操作的结果，该操作将当前裁剪区域与指定的区域合并。

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 指定要合并的区域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定合并操作 |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) 方法


将当前 [Graphics](../) 对象表示的绘图表面的裁剪区域设置为指定操作的结果，该操作将当前裁剪区域与指定的区域合并。

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 指定要合并的区域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定合并操作 |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) 方法


未实现。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) 方法


将当前 [Graphics](../) 对象表示的绘图表面的裁剪区域设置为指定操作的结果，该操作将当前裁剪区域与由图形路径指定的区域合并。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 指定要合并的区域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定合并操作 |

## 参见

* 枚举 [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Region](../../region/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 类 [RectangleF](../../rectanglef/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)