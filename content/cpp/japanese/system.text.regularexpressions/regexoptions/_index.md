---
title: RegexOptions
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現オプション。
type: docs
weight: 118
url: /ja/system.text.regularexpressions/regexoptions/
---
## RegexOptions 列挙型

[Regex](../regex/) オプション。

```cpp
enum class RegexOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 既定の動作です。 |
| Compiled | 1 | パフォーマンス向上のために正規表現をコンパイルします。デフォルトで常に実行されます。 |
| CultureInvariant | 2 | 文化に依存しないマッチングを使用します。無視されます。 |
| ECMAScript | 4 | ECMAScript 構文を使用します。無視されます。 |
| ExplicitCapture | 8 | 明示的なキャプチャのみです。無視されます。 |
| IgnoreCase | 16 | マッチング時に大文字と小文字を区別しません。 |
| IgnorePatternWhitespace | 32 | パターン内の空白文字を無視します。サポートされていません。 |
| Multiline | 64 | '^' と '$' を文字列全体ではなく行の開始と終了として扱います。 |
| RightToLeft | 128 | 右から左へのマッチングです。サポートされていません。 |
| Singleline | 256 | '.' が例外なくすべての文字に一致するようにします（通常、改行文字は一致しません）。 |

## 参照

* 名前空間 [System::Text::RegularExpressions](../)
* ライブラリ [Aspose.Slides](../../)