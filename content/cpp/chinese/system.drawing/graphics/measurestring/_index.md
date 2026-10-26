---
title: MeasureString()
second_title: Aspose.Slides C++ API 参考
description: 返回在指定字体和指定格式下绘制指定字符串的大小。
type: docs
weight: 521
url: /zh/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

返回在指定字体和指定格式下绘制指定字符串的大小。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 要计算大小的字符串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用于绘制字符串的字体 |
| origin | [PointF](../../pointf/) const\& | 指定字符串左上角的位置 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字符串格式 |

### 返回值

一个 [SizeF](../../sizef/) 对象，表示以当前 Grapphics 对象的 PageUnit 属性指定的测量单位表示的字符串大小。

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

返回在指定字体和指定格式下绘制指定字符串的大小。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 要计算大小的字符串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用于绘制字符串的字体 |
| width | int | 字符串的最大宽度 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字符串格式 |

### 返回值

一个 [SizeF](../../sizef/) 对象，表示以当前 Grapphics 对象的 PageUnit 属性指定的测量单位表示的字符串大小。

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

未实现。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

返回在指定字体和指定格式下绘制指定字符串的大小。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 要计算大小的字符串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用于绘制字符串的字体 |
| layoutArea | [SizeF](../../sizef/) const\& | 字符串的最大布局区域 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字符串格式 |

### 返回值

一个 [SizeF](../../sizef/) 对象，表示以当前 Grapphics 对象的 PageUnit 属性指定的测量单位表示的字符串大小。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [SizeF](../../sizef/)
* 类 [String](../../../system/string/)
* 类 [Font](../../font/)
* 类 [PointF](../../pointf/)
* 类 [StringFormat](../../stringformat/)
* 类 [Graphics](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)