---
title: DrawString()
second_title: Aspose.Slides for C++ API 参考
description: 在指定位置使用指定的字体和画刷绘制指定的字符串。
type: docs
weight: 365
url: /zh/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定位置使用指定的字体和画刷绘制指定的字符串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要绘制的字符串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字体 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于绘图的 [Brush](../../brush/) 对象 |
| topLeft | [PointF](../../pointf/) | 指定绘制字符串左上角的位置 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字符串的格式 |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定的矩形中使用指定的字体和画刷绘制指定的字符串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要绘制的字符串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字体 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于绘图的 [Brush](../../brush/) 对象 |
| layoutRectangle | [RectangleF](../../rectanglef/) | 指定绘制字符串的矩形区域 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字符串的格式 |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定位置使用指定的字体和画刷绘制指定的字符串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要绘制的字符串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字体 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于绘图的 [Brush](../../brush/) 对象 |
| x | **float** | 绘制字符串左上角的 X 坐标 |
| y | **float** | 绘制字符串左上角的 Y 坐标 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字符串的格式 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Font](../../font/)
* 类 [Brush](../../brush/)
* 类 [PointF](../../pointf/)
* 类 [StringFormat](../../stringformat/)
* 类 [Graphics](../)
* 类 [RectangleF](../../rectanglef/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)