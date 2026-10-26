---
title: MeasureString()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォントと指定された書式で描画されたときの、指定された文字列のサイズを返します。
type: docs
weight: 521
url: /ja/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

指定されたフォントと指定された書式で描画されたときの、指定された文字列のサイズを返します。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | サイズを計算する文字列 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 文字列の描画に使用するフォント |
| origin | [PointF](../../pointf/) const\& | 文字列の左上隅の位置を指定します |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 文字列の書式を指定します |

### 戻り値

現在の Graphics オブジェクトの PageUnit プロパティで指定された測定単位で文字列のサイズを表す [SizeF](../../sizef/) オブジェクトです。

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

指定されたフォントと指定された書式で描画されたときの、指定された文字列のサイズを返します。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | サイズを計算する文字列 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 文字列の描画に使用するフォント |
| width | int | 文字列の最大幅を指定します |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 文字列の書式を指定します |

### 戻り値

現在の Graphics オブジェクトの PageUnit プロパティで指定された測定単位で文字列のサイズを表す [SizeF](../../sizef/) オブジェクトです。

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

未実装です。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

指定されたフォントと指定された書式で描画されたときの、指定された文字列のサイズを返します。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | サイズを計算する文字列 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 文字列の描画に使用するフォント |
| layoutArea | [SizeF](../../sizef/) const\& | 文字列の最大レイアウト領域を指定します |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 文字列の書式を指定します |

### 戻り値

現在の Graphics オブジェクトの PageUnit プロパティで指定された測定単位で文字列のサイズを表す [SizeF](../../sizef/) オブジェクトです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)