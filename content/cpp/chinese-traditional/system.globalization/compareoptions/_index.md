---
title: CompareOptions
second_title: Aspose.Slides for C++ API 參考
description: 字串比較選項。
type: docs
weight: 430
url: /zh-hant/system.globalization/compareoptions/
---
## CompareOptions enum

[String](../../system/string/) 比較選項。

```cpp
enum class CompareOptions : int32_t
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 無特別選項。 |
| IgnoreCase | 1 | 忽略大小寫。 |
| IgnoreNonSpace | 2 | 忽略非間距組合字元，例如變音符號。 |
| IgnoreSymbols | 4 | 包括空白字元、標點符號等。 |
| IgnoreKanaType | 8 | 忽略假名類型（日語）。 |
| IgnoreWidth | 16 | 在比較字串時忽略字元寬度。 |
| OrdinalIgnoreCase | 268435456 | 在序數比較時忽略大小寫差異。 |
| StringSort | 536870912 | 使用字串排序演算法比較字元。 |
| Ordinal | 1073741824 | 在第一次比較時直接比較 UTF 代碼。 |

## 另見

* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)