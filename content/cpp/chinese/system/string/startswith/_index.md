---
title: StartsWith()
second_title: Aspose.Slides for C++ API 参考
description: 检查字符串是否以指定子串开始。
type: docs
weight: 469
url: /zh/system/string/startswith/
---
## String::StartsWith(const String\&) const method

检查字符串是否以指定子串开始。

```cpp
bool System::String::StartsWith(const String &value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字符串。 |

### 返回值

如果字符串以指定子串开始则返回 true，否则返回 false。

## String::StartsWith(const String\&, System::StringComparison) const method

检查字符串是否以指定子串开始。

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字符串。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式，详情请参见 [System::StringComparison](../../stringcomparison/)。 |

### 返回值

如果字符串以指定子串开始则返回 true，否则返回 false。

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

检查字符串是否以指定子串开始。

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../)\& | 查找字符串。 |
| ignoreCase | **bool** | 指定比较是否不区分大小写。 |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 执行字符串比较时使用的区域性。 |

### 返回值

如果字符串以指定子串开始则返回 true，否则返回 false。

## 另请参见

* 枚举 [StringComparison](../../stringcomparison/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)