---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等价的 32 位无符号整数。
type: docs
weight: 14
url: /zh/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method

将包含数字字符串表示的指定字符串转换为等价的 32 位无符号整数。

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **uint32_t**\& | 指向 32 位无符号整数变量的引用，转换结果将写入该变量。 |

### 返回值

如果转换成功则返回 true，否则 - false。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method

使用提供的格式信息和数字样式，将包含数字字符串表示的指定字符串转换为等价的 32 位无符号整数。

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的位组合，指定数字字符串表示的允许样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |
| result | **uint32_t**\& | 指向 32 位无符号整数变量的引用，转换结果将写入该变量。 |

### 返回值

如果转换成功则返回 true，否则 - false。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## 另见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 结构体 [UInt32](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)