---
title: AddString()
second_title: Aspose.Slides for C++ API 參考
description: 將一段文字字串新增至目前物件所代表的路徑。
type: docs
weight: 170
url: /zh-hant/system.drawing.drawing2d/graphicspath/addstring/
---
## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) 方法


將一段文字字串新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Point origin, const SharedPtr<StringFormat> &stringFormat)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要新增的文字 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用於繪製文字的字型族 |
| style | int | 指定要使用之字型樣式的 FontStyle 列舉值 |
| emSize | **float** | 字串中每個字元所屬的 EM 方形盒的高度 |
| origin | [Point](../../../system.drawing/point/) | 指定文字開始的位置 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) 方法


將一段文字字串新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, PointF origin, const SharedPtr<StringFormat> &stringFormat)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要新增的文字 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用於繪製文字的字型族 |
| style | int | 指定要使用之字型樣式的 FontStyle 列舉值 |
| emSize | **float** | 字串中每個字元所屬的 EM 方形盒的高度 |
| origin | [PointF](../../../system.drawing/pointf/) | 指定文字開始的位置 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) 方法


將一段文字字串新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Rectangle layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要新增的文字 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用於繪製文字的字型族 |
| style | int | 指定要使用之字型樣式的 FontStyle 列舉值 |
| emSize | **float** | 字串中每個字元所屬的 EM 方形盒的高度 |
| layoutRect | [Rectangle](../../../system.drawing/rectangle/) | 限定文字的矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字串的格式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) 方法


將一段文字字串新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 要新增的文字 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 用於繪製文字的字型族 |
| style | int | 指定要使用之字型樣式的 FontStyle 列舉值 |
| emSize | **float** | 字串中每個字元所屬的 EM 方形盒的高度 |
| layoutRect | [RectangleF](../../../system.drawing/rectanglef/) | 限定文字的矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 字串的格式 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [FontFamily](../../../system.drawing/fontfamily/)
* 類別 [Point](../../../system.drawing/point/)
* 類別 [StringFormat](../../../system.drawing/stringformat/)
* 類別 [GraphicsPath](../)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [Rectangle](../../../system.drawing/rectangle/)
* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)