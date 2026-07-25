---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列内の文字位置を境界とする領域の配列を返します。
type: docs
weight: 508
url: /ja/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) メソッド

指定された文字列内の文字位置を境界とする領域の配列を返します。

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 測定対象の文字列 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 文字列の測定に使用されるフォント |
| layoutRect | [RectangleF](../../rectanglef/) | 文字列の測定中に使用されるレイアウト矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | 測定対象の文字範囲を含む文字列フォーマット |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Region](../../region/)
* クラス [String](../../../system/string/)
* クラス [Font](../../font/)
* クラス [RectangleF](../../rectanglef/)
* クラス [StringFormat](../../stringformat/)
* クラス [Graphics](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)