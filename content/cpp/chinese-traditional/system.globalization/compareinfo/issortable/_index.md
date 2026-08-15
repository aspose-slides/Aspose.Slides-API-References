---
title: IsSortable()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查指定的字元是否可排序。
type: docs
weight: 196
url: /zh-hant/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) 方法

檢查指定的字元是否可排序。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char16_t | Unicode 字元。 |

### 傳回值

如果 **ch** 可排序則回傳 True；否則回傳 false。

## CompareInfo::IsSortable(const String\&) 方法

檢查指定的字串是否可排序。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 字串。 |

### 傳回值

如果 **text** 非空且 **text** 中的所有字元皆可排序則回傳 True；否則回傳 false。

## 另請參閱

* 類別 [CompareInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)