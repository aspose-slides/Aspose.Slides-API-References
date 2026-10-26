---
title: Split()
second_title: Aspose.Slides for C++ API 參考文件
description: 以正則表達式匹配分割字串。
type: docs
weight: 105
url: /zh-hant/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) 方法

依正則表達式匹配分割字串。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) 進行分割。 |

### 返回值

[Array](../../../system/array/)，表示匹配之間的子字串。

## Regex::Split(const String\&, int) 方法

依正則表達式匹配分割字串。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) 進行分割。 |
| count | int | 子字串的數量限制。 |

### 返回值

[Array](../../../system/array/)，表示匹配之間的子字串。

## Regex::Split(const String\&, int, int) 方法

根據 [Regex](../) 建構式中指定的正則表達式，將輸入字串最多分割指定次數，產生子字串陣列。正則表達式模式的搜尋會從輸入字串的指定字符位置開始。

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 要分割的字串。 |
| count | int | 分割可發生的最大次數。 |
| startat | int | 搜尋在輸入字串中開始的字符位置。 |

### 返回值

字串陣列。

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) 方法

根據正則表達式分割字串。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正則表達式模式。 |
| options | [RegexOptions](../../regexoptions/) | 匹配選項。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超時時間。 |

### 返回值

[Array](../../../system/array/)，表示匹配之間的字串。

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) 方法

根據正則表達式分割字串。

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 輸入字串。 |
| pattern | const [String](../../../system/string/)\& | 正則表達式模式。 |
| count | int | [Match](../../match/) 數量限制。 |
| options | [RegexOptions](../../regexoptions/) | 匹配選項。 |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 超時時間。 |

### 返回值

[Array](../../../system/array/)，表示匹配之間的字串。

## 另見

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)