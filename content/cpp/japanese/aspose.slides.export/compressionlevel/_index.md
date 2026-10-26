---
title: CompressionLevel
second_title: Aspose.Slides for C++ API リファレンス
description: OpenXML ファイルの ZIP 圧縮レベルを指定します。レベルが高いほど、圧縮率が向上しますが、処理が遅くなります。
type: docs
weight: 846
url: /ja/aspose.slides.export/compressionlevel/
---
## CompressionLevel 列挙型

OpenXML ファイルの ZIP 圧縮レベルを指定します。レベルが高いほど、圧縮率が向上しますが、処理が遅くなります。

```cpp
enum class CompressionLevel
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 圧縮は適用されません。ファイルはそのまま保存されます。 |
| Level1 | 1 | 最低の圧縮率で最速の圧縮です。 |
| Level2 | 2 | [CompressionLevel::Level1](./) よりわずかに高い圧縮率で高速な圧縮です。 |
| Level3 | 3 | [CompressionLevel::Level2](./) より良い圧縮を提供し、パフォーマンスへの影響は中程度です。 |
| Level4 | 4 | [CompressionLevel::Level3](./) より良い圧縮を提供します。 |
| Level5 | 5 | [CompressionLevel::Level4](./) より圧縮が向上し、処理時間が追加されます。 |
| Level6 | 6 | 標準的な圧縮で、圧縮速度とファイルサイズのバランスが良好です。デフォルトの圧縮レベルです。 |
| Level7 | 7 | [CompressionLevel::Level6](./) より高い圧縮を提供しますが、処理は遅くなります。 |
| Level8 | 8 | [CompressionLevel::Level7](./) より高い圧縮を提供します。 |
| Level9 | 9 | 最大の圧縮です。最も小さいファイルサイズが得られますが、処理速度は最も遅くなります。 |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)