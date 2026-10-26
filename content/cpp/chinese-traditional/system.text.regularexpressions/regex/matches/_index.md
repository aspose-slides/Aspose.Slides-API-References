---
title: Matches()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過重複匹配取得在給定字串中的所有正則表達式匹配。
type: docs
weight: 79
url: /zh-hant/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) 方法

取得在給定字串中正則表達式的所有比對，透過重複匹配。

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| startat | int | [Index](../../../system/index/) 以開始匹配。 |

### 回傳值

所有找到的比對集合。

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 方法

取得字串與模式之間的所有比對。

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正則表達式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配選項。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 逾時。 |
| startat | int | [Match](../../match/) 起始位置。 |
| length | int | 要檢查的字元數量 (0 表示取消限制)。 |

### 回傳值

所有透過重複匹配取得的比對。

## 另請參閱

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)