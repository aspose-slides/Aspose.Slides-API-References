---
title: StartsWith()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查字串是否以指定的子字串開始。
type: docs
weight: 469
url: /zh-hant/system/string/startswith/
---
## String::StartsWith(const String\&) const 方法

檢查字串是否以指定的子字串開始。

```cpp
bool System::String::StartsWith(const String &value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字串。 |

### 返回值

若字串以指定的子字串開始則返回 true，否則返回 false。

## String::StartsWith(const String\&, System::StringComparison) const 方法

檢查字串是否以指定的子字串開始。

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字串。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式，有關詳細資訊，請參閱 [System::StringComparison](../../stringcomparison/)。 |

### 返回值

若字串以指定的子字串開始則返回 true，否則返回 false。

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const 方法

檢查字串是否以指定的子字串開始。

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字串。 |
| ignoreCase | **bool** | 指定比較是否不區分大小寫。 |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 執行字串比較時使用的文化。 |

### 返回值

若字串以指定的子字串開始則返回 true，否則返回 false。

## 另請參閱

* 列舉 [StringComparison](../../stringcomparison/)
* 類型別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)