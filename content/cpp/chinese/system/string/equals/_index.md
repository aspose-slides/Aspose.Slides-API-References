---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 字符串相等比较。支持 StringComparison 枚举提供的多种模式。
type: docs
weight: 391
url: /zh/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const 方法

[String](../) 相等比较。提供的 StringComparison 枚举的多种模式受支持。

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用于与当前对象比较。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式（有关详细信息，请参见 [System::StringComparison](../../stringcomparison/)）。 |

### 返回值

若字符串在使用所选比较类型时匹配则返回 true，否则返回 false。

## String::Equals(const String\&) const 方法

[String](../) 相等比较。使用 [System::StringComparison::Ordinal](../../stringcomparison/) 比较模式。

```cpp
bool System::String::Equals(const String &str) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用于与当前对象比较。 |

### 返回值

若字符串匹配则返回 true，否则返回 false。

## String::Equals(const String\&, const String\&) 方法

使用 Ordial 比较模式对两个字符串进行相等比较。

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比较的第一个字符串。 |
| strB | const [String](../)\& | 要比较的第二个字符串。 |

### 返回值

若字符串匹配则返回 true，否则返回 false。

## String::Equals(const String\&, const String\&, System::StringComparison) 方法

对两个字符串进行相等比较。

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比较的第一个字符串。 |
| strB | const [String](../)\& | 要比较的第二个字符串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

若字符串匹配则返回 true，否则返回 false。

## 另见

* 枚举 [StringComparison](../../stringcomparison/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)