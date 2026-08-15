---
title: Match()
second_title: Aspose.Slides for C++ API 參考
description: 將正則表達式與字串比對。
type: docs
weight: 66
url: /zh-hant/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) 方法

將正則表達式與字串比對。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目標字串。 |

### 返回值

[Match](../../match/) 值，包含匹配狀態和子匹配。

## Regex::Match(const String\&, int, int) 方法

將正則表達式與字串比對。

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 目標字串。 |
| startat | int | 起始索引。 |
| length | int | 要檢查的字元數 (0 表示檢查整個字串)。 |

### 返回值

[Match](../../match/) 值，包含匹配狀態和子匹配。

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 方法

將字串與模式比對。

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正則表達式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配選項。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超時。 |
| startat | int | [Match](../../match/) 起始位置。 |
| length | int | 要檢查的字元數 (0 表示無限制)。 |

### 返回值

找到的第一個匹配。

## 另見

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* 類別 [String](../../../system/string/)
* 類別 [Regex](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)