---
title: Zip64Mode
second_title: Aspose.Slides for C++ API リファレンス
description: OpenXML ファイルに対して ZIP64 フォーマット拡張機能を使用するタイミングを指定します。
type: docs
weight: 1119
url: /ja/aspose.slides.export/zip64mode/
---
## Zip64Mode 列挙型


OpenXML ファイルに対して ZIP64 フォーマット拡張機能を使用するタイミングを指定します。

```cpp
enum class Zip64Mode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Never | 0 | ZIP64 フォーマット拡張機能を使用しません。 |
| IfNecessary | 1 | 必要に応じて ZIP64 フォーマット拡張機能を使用します。 |
| Always | 2 | 常に ZIP64 フォーマット拡張機能を使用します。 |

## 備考


OpenXML ファイルは ZIP アーカイブであり、ファイルの非圧縮サイズ、圧縮サイズ、アーカイブ全体のサイズにそれぞれ 4 GB (2^32 バイト) の上限があり、アーカイブ内のファイル数は 65 535 (2^16-1) に制限されています。ZIP64 フォーマット拡張機能により、上限が 2^64 に拡大されます。 
## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)