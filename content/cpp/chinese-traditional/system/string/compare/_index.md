---
title: Compare()
second_title: Aspose.Slides for C++ API 參考文件
description: 比較兩個子字串，返回小於、等於或大於的結果。
type: docs
weight: 820
url: /zh-hant/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) 方法

比較兩個子字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| indexA | int | 第一個字串子字串的起始位置。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| indexB | int | 第二個字串子字串的起始位置。 |
| length | int | 要比較的字元數。 |
| ignoreCase | **bool** | 指定比較是否忽略大小寫。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 方法

比較兩個子字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| indexA | int | 第一個字串子字串的起始位置。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| indexB | int | 第二個字串子字串的起始位置。 |
| length | int | 要比較的字元數。 |
| ignoreCase | **bool** | 指定比較是否忽略大小寫。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 比較時使用的文化資訊。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## String::Compare(const String\&, const String\&, System::StringComparison) 方法

比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) 方法

比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| indexA | int | 第一個字串子字串的起始位置。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| indexB | int | 第二個字串子字串的起始位置。 |
| length | int | 要比較的字元數。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## String::Compare(const String\&, const String\&, bool) 方法

比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| ignoreCase | **bool** | 指定比較是否忽略大小寫。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 方法

比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| ignoreCase | **bool** | 指定比較是否忽略大小寫。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 比較時使用的文化資訊。 |

### 返回值

若第一個子字串小於第二個則返回負值，若相等則返回零，否則返回正值。

## 另見

* 列舉 [StringComparison](../../stringcomparison/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)