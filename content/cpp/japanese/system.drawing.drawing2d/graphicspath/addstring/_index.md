---
title: AddString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すパスにテキスト文字列を追加します。
type: docs
weight: 170
url: /ja/system.drawing.drawing2d/graphicspath/addstring/
---
## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) メソッド

現在のオブジェクトが表すパスにテキスト文字列を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Point origin, const SharedPtr<StringFormat> &stringFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 追加するテキスト |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | テキスト描画に使用されるフォントファミリ |
| style | int | 使用するフォントスタイルを指定する FontStyle 列挙値 |
| emSize | **float** | 文字列の各文字を囲む em 四角形ボックスの高さ |
| origin | [Point](../../../system.drawing/point/) | テキストの開始位置を指定します |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 文字列の書式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) メソッド

現在のオブジェクトが表すパスにテキスト文字列を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, PointF origin, const SharedPtr<StringFormat> &stringFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 追加するテキスト |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | テキスト描画に使用されるフォントファミリ |
| style | int | 使用するフォントスタイルを指定する FontStyle 列挙値 |
| emSize | **float** | 文字列の各文字を囲む em 四角形ボックスの高さ |
| origin | [PointF](../../../system.drawing/pointf/) | テキストの開始位置を指定します |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 文字列の書式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) メソッド

現在のオブジェクトが表すパスにテキスト文字列を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Rectangle layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 追加するテキスト |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | テキスト描画に使用されるフォントファミリ |
| style | int | 使用するフォントスタイルを指定する FontStyle 列挙値 |
| emSize | **float** | 文字列の各文字を囲む em 四角形ボックスの高さ |
| layoutRect | [Rectangle](../../../system.drawing/rectangle/) | テキストを囲む矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 文字列の書式 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) メソッド

現在のオブジェクトが表すパスにテキスト文字列を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 追加するテキスト |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | テキスト描画に使用されるフォントファミリ |
| style | int | 使用するフォントスタイルを指定する FontStyle 列挙値 |
| emSize | **float** | 文字列の各文字を囲む em 四角形ボックスの高さ |
| layoutRect | [RectangleF](../../../system.drawing/rectanglef/) | テキストを囲む矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 文字列の書式 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [FontFamily](../../../system.drawing/fontfamily/)
* クラス [Point](../../../system.drawing/point/)
* クラス [StringFormat](../../../system.drawing/stringformat/)
* クラス [GraphicsPath](../)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [Rectangle](../../../system.drawing/rectangle/)
* クラス [RectangleF](../../../system.drawing/rectanglef/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)