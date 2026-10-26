---
title: BlackWhiteConversionMode
second_title: Aspose.Slides for C++ API リファレンス
description: スライドの画像を二値画像に変換する方法を制御するオプションを提供します。
type: docs
weight: 820
url: /ja/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

スライドの画像を二値画像に変換する方法を制御するオプションを提供します。

```cpp
enum class BlackWhiteConversionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | 0 | 変換アルゴリズムが指定されていません。TIFF コーデックで実装されたアルゴリズムが使用されます。(Default) |
| Dithering | 1 | ディザリングアルゴリズム（Floyd-Steinberg）を指定します。 |
| DitheringFloydSteinberg | 2 | Floyd-Steinberg ディザリングアルゴリズムを指定します。 |
| Auto | 3 | 自動的に計算された閾値アルゴリズム（Otsu）を指定します。 |
| AutoOtsu | 4 | 自動的に計算された Otsu の閾値アルゴリズムを指定します。 |
| Threshold25 | 5 | 静的閾値アルゴリズム（25%）を指定します。 |
| Threshold50 | 6 | 静的閾値アルゴリズム（50%）を指定します。 |
| Threshold75 | 7 | 静的閾値アルゴリズム（75%）を指定します。 |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)