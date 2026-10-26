---
title: IsMatch()
second_title: Aspose.Slides for C++ API 參考文件
description: 將正規表達式與字串比對。
type: docs
weight: 53
url: /zh-hant/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) 方法

將正規表達式與字串比對。

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目標字串。 |
| startat | int | 起始索引。 |

### 傳回值

如果字串符合正規表達式則回傳 true，否則回傳 false。

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) 方法

檢查字串是否符合模式。

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正則表達式樣式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配選項。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 逾時。 |
| startat | int | [Match](../../match/) 起始位置。 |

### 傳回值

如果找到匹配則回傳 true，否則回傳 false。

## 另請參閱

* 列舉 [RegexOptions](../../regexoptions/)
* 類別 [String](../../../system/string/)
* 類別 [Regex](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Text::RegularExpressions](../../)
* 函式庫 [Aspose.Slides](../../../)