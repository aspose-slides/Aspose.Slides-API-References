---
title: IsSuffix()
second_title: Aspose.Slides C++ API 參考
description: 檢查指定的字串是否以指定的後綴結尾，使用指定的比較選項。
type: docs
weight: 118
url: /zh-hant/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const 方法


檢查指定的字串是否以指定的後綴結尾，使用指定的比較選項。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 來源字串。 |
| suffix | const [String](../../../system/string/)\& | 後綴字串。 |
| options | [CompareOptions](../../compareoptions/) | 比較選項。 |

### 返回值

如果字串以後綴結尾則返回 True；否則返回 false。

## CompareInfo::IsSuffix(const String\&, const String\&) const 方法


檢查指定的字串是否以指定的後綴結尾。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 來源字串。 |
| suffix | const [String](../../../system/string/)\& | 後綴字串。 |

### 返回值

如果字串以後綴結尾則返回 True；否則返回 false。

## 另見

* 列舉 [CompareOptions](../../compareoptions/)
* 類別 [String](../../../system/string/)
* 類別 [CompareInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)