---
title: CompareOptions
second_title: Aspose.Slides の C++ API リファレンス
description: 文字列比較オプション。
type: docs
weight: 430
url: /ja/system.globalization/compareoptions/
---
## CompareOptions 列挙型

[String](../../system/string/) 比較オプション。

```cpp
enum class CompareOptions : int32_t
```

### 値

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 特別なオプションはありません。 |
| IgnoreCase | 1 | 大文字と小文字を区別しない。 |
| IgnoreNonSpace | 2 | 結合文字（非間隔文字）、例: ダイアクリティックを無視する。 |
| IgnoreSymbols | 4 | 空白文字や句読点記号などを含む。 |
| IgnoreKanaType | 8 | かな種別を無視する（日本語）。 |
| IgnoreWidth | 16 | 文字幅の違いを無視する。 |
| OrdinalIgnoreCase | 268435456 | 大文字小文字の違いを無視した順序比較。 |
| StringSort | 536870912 | 文字の比較に文字列ソートアルゴリズムを使用する。 |
| Ordinal | 1073741824 | 最初の比較で UTF コードを直接比較する。 |

## 参照

* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)