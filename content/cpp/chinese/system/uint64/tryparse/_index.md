---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的包含数字字符串表示的字符串转换为等效的 64 位无符号整数。
type: docs
weight: 14
url: /zh/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) method

将指定的包含数字字符串表示的字符串转换为等效的 64 位无符号整数。

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **uint64_t**\& | 用于存放转换结果的 64 位无符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) method

将指定的包含数字字符串表示的字符串转换为等效的 64 位无符号整数，使用提供的格式信息和数字样式。

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定数字字符串表示的允许样式的 NumberStyles 枚举值的按位组合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针。 |
| result | **uint64_t**\& | 用于存放转换结果的 64 位无符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## 另请参见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 结构体 [UInt64](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)