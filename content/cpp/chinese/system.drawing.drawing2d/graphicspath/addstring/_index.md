---
title: AddString()
second_title: Aspose.Slides for C++ API 参考
description: 向当前对象表示的路径添加一段文本。
type: docs
weight: 170
url: /zh/system.drawing.drawing2d/graphicspath/addstring/
---
## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) method

向当前对象表示的路径添加一段文本。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Point origin, const SharedPtr<StringFormat> &stringFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要添加的文本 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用于绘制文本的字体族 |
| style | int | 指定要使用的字体样式的 FontStyle 枚举值 |
| emSize | **float** | 包围字符串中每个字符的 em 方框的高度 |
| origin | [Point](../../../system.drawing/point/) | 指定文本开始的位置 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字符串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) method

向当前对象表示的路径添加一段文本。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, PointF origin, const SharedPtr<StringFormat> &stringFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要添加的文本 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用于绘制文本的字体族 |
| style | int | 指定要使用的字体样式的 FontStyle 枚举值 |
| emSize | **float** | 包围字符串中每个字符的 em 方框的高度 |
| origin | [PointF](../../../system.drawing/pointf/) | 指定文本开始的位置 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字符串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) method

向当前对象表示的路径添加一段文本。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Rectangle layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要添加的文本 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用于绘制文本的字体族 |
| style | int | 指定要使用的字体样式的 FontStyle 枚举值 |
| emSize | **float** | 包围字符串中每个字符的 em 方框的高度 |
| layoutRect | [Rectangle](../../../system.drawing/rectangle/) | 包围文本的矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字符串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) method

向当前对象表示的路径添加一段文本。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要添加的文本 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用于绘制文本的字体族 |
| style | int | 指定要使用的字体样式的 FontStyle 枚举值 |
| emSize | **float** | 包围字符串中每个字符的 em 方框的高度 |
| layoutRect | [RectangleF](../../../system.drawing/rectanglef/) | 包围文本的矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字符串的格式 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [FontFamily](../../../system.drawing/fontfamily/)
* 类 [Point](../../../system.drawing/point/)
* 类 [StringFormat](../../../system.drawing/stringformat/)
* 类 [GraphicsPath](../)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [Rectangle](../../../system.drawing/rectangle/)
* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)