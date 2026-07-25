---
title: DrawString()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォントとブラシを使用して、指定された場所に指定された文字列を描画します。
type: docs
weight: 365
url: /ja/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) メソッド

指定されたフォントとブラシを使用して、指定された場所に指定された文字列を描画します。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 描画する文字列 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 使用するフォント |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 描画に使用する [Brush](../../brush/) オブジェクト |
| topLeft | [PointF](../../pointf/) | 描画された文字列の左上隅の位置を指定します |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 文字列の書式を指定します |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) メソッド

指定されたフォントとブラシを使用して、指定された矩形内に指定された文字列を描画します。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 描画する文字列 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 使用するフォント |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 描画に使用する [Brush](../../brush/) オブジェクト |
| layoutRectangle | [RectangleF](../../rectanglef/) | 文字列を描画する矩形を指定します |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 文字列の書式を指定します |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) メソッド

指定されたフォントとブラシを使用して、指定された場所に指定された文字列を描画します。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 描画する文字列 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 使用するフォント |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 描画に使用する [Brush](../../brush/) オブジェクト |
| x | **float** | 描画された文字列の左上隅の X 座標 |
| y | **float** | 描画された文字列の左上隅の Y 座標 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 文字列の書式を指定します |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Font](../../font/)
* クラス [Brush](../../brush/)
* クラス [PointF](../../pointf/)
* クラス [StringFormat](../../stringformat/)
* クラス [Graphics](../)
* クラス [RectangleF](../../rectanglef/)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)