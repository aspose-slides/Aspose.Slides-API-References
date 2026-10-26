---
title: IsPrefix()
second_title: Aspose.Slides for C++ API 參考
description: 檢查指定的字串是否以指定的前綴開始，使用指定的比較選項。
type: docs
weight: 105
url: /zh-hant/system.globalization/compareinfo/isprefix/
---
## CompareInfo::IsPrefix(const String&, const String&, CompareOptions) const 方法

檢查指定的字串是否以指定的前綴開始，使用指定的比較選項。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix, CompareOptions options) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 來源字串。 |
| prefix | const [String](../../../system/string/)\& | 前綴字串。 |
| options | [CompareOptions](../../compareoptions/) | 比較選項。 |

### 回傳值

True if string starts with prefix; otherwise false.

## CompareInfo::IsPrefix(const String&, const String&) const 方法

檢查指定的字串是否以指定的前綴開始。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 來源字串。 |
| prefix | const [String](../../../system/string/)\& | 前綴字串。 |

### 回傳值

True if string starts with prefix; otherwise false.

## 另請參閱

* Enum [CompareOptions](../../compareoptions/)
* 類別 [String](../../../system/string/)
* 類別 [CompareInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)