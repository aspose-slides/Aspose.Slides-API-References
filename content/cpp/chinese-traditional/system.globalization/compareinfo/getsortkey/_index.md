---
title: GetSortKey()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的比較選項取得指定字串的 SortKey 物件。
type: docs
weight: 79
url: /zh-hant/system.globalization/compareinfo/getsortkey/
---
## CompareInfo::GetSortKey(const String\&, CompareOptions) const 方法

取得指定字串使用指定比較選項的 [SortKey](../../sortkey/) 物件。

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value, CompareOptions options) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 輸入字串。 |
| options | [CompareOptions](../../compareoptions/) | 比較選項。 |

### 傳回值

[SortKey](../../sortkey/) 物件。

## CompareInfo::GetSortKey(const String\&) const 方法

取得指定字串的 [SortKey](../../sortkey/) 物件。

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 輸入字串。 |

### 傳回值

[SortKey](../../sortkey/) 物件。

## 另請參閱

* 列舉 [CompareOptions](../../compareoptions/)
* 類型別名 [SortKeyPtr](../../sortkeyptr/)
* 類別 [String](../../../system/string/)
* 類別 [CompareInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)