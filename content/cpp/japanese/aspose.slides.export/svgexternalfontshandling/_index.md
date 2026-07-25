---
title: SvgExternalFontsHandling
second_title: C++ 用 Aspose.Slides API リファレンス
description: テキスト描画に使用される外部フォントを処理する方法を表します。
type: docs
weight: 1080
url: /ja/aspose.slides.export/svgexternalfontshandling/
---
## SvgExternalFontsHandling 列挙体

テキスト描画に使用される外部フォントを処理する方法を表します。

```cpp
enum class SvgExternalFontsHandling
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AddLinksToFontFiles | 0 | SVG ファイルの style セクションに別々のフォントファイルへのリンクを追加します。 |
| Embed | 1 | フォントデータを直接 SVG ファイルに保存します。このオプションを使用する前に、すべての外部フォントのライセンス契約を確認してください。 |
| Vectorize | 2 | 外部フォントを使用したすべてのテキストをグラフィックとして保存します。 |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)