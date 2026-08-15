---
title: EndsWith()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查字串是否以指定的子字串結尾。
type: docs
weight: 482
url: /zh-hant/system/string/endswith/
---
## String::EndsWith(const String\&) const method

檢查字串是否以指定的子字串結尾。

```cpp
bool System::String::EndsWith(const String &value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的字串。 |

### 返回值

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, System::StringComparison) const method

檢查字串是否以指定的子字串結尾。

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的字串。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式，詳見 [System::StringComparison](../../stringcomparison/)。 |

### 返回值

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

檢查字串是否以指定的子字串結尾。

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的字串。 |
| ignoreCase | **bool** | 指定比較是否不區分大小寫。 |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 執行字串比較時使用的文化資訊。 |

### 返回值

true if string ends with specified substring, false otherwise.

## 參見

* 列舉 [StringComparison](../../stringcomparison/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)