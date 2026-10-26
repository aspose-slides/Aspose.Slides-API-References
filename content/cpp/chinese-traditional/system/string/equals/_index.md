---
title: Equals()
second_title: Aspose.Slides for C++ API 參考
description: 字串相等性比較。支援由 StringComparison 列舉提供的多種模式。
type: docs
weight: 391
url: /zh-hant/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const 方法

[String](../) 相等比較。提供了 StringComparison 列舉的多種模式。

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用於與目前的字串比較。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式（詳情請參閱 [System::StringComparison](../../stringcomparison/)）。 |

### 返回值

如果字串在使用選取的比較類型時匹配則返回 true，否則返回 false。

## String::Equals(const String\&) const 方法

[String](../) 相等比較。使用 [System::StringComparison::Ordinal](../../stringcomparison/) 比較模式。

```cpp
bool System::String::Equals(const String &str) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用於與目前的字串比較。 |

### 返回值

如果字串匹配則返回 true，否則返回 false。

## String::Equals(const String\&, const String\&) 方法

使用 Ordial 比較模式對兩個字串進行相等比較。

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | 第一個要比較的字串。 |
| strB | const [String](../)\& | 第二個要比較的字串。 |

### 返回值

如果字串匹配則返回 true，否則返回 false。

## String::Equals(const String\&, const String\&, System::StringComparison) 方法

對兩個字串進行相等比較。

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | 第一個要比較的字串。 |
| strB | const [String](../)\& | 第二個要比較的字串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

如果字串匹配則返回 true，否則返回 false。

## 另請參閱

* 列舉 [StringComparison](../../stringcomparison/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)