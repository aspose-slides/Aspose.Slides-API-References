---
title: RegexOptions
second_title: Aspose.Slides C++ API 參考手冊
description: 正則表達式選項。
type: docs
weight: 118
url: /zh-hant/system.text.regularexpressions/regexoptions/
---
## RegexOptions 列舉

[Regex](../regex/) 選項.

```cpp
enum class RegexOptions
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 預設行為。 |
| Compiled | 1 | 編譯正則表達式以提升效能。預設情況下始終執行。 |
| CultureInvariant | 2 | 使用與語系無關的匹配。已忽略。 |
| ECMAScript | 4 | 使用 ECMAScript 語法。已忽略。 |
| ExplicitCapture | 8 | 僅限顯式捕獲。已忽略。 |
| IgnoreCase | 16 | 匹配時忽略大小寫。 |
| IgnorePatternWhitespace | 32 | 忽略模式中的空白字元。不支援。 |
| Multiline | 64 | 將 '^' 和 '$' 視為行的開始和結束，而非整個字串的開始和結束。 |
| RightToLeft | 128 | 從右至左匹配。不支援。 |
| Singleline | 256 | 使 '.' 匹配任何字元，沒有例外（通常，換行字元不會被匹配）。 |

## 另請參閱

* 命名空間 [System::Text::RegularExpressions](../)
* 函式庫 [Aspose.Slides](../../)