---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等效的 16 位有符号整数。
type: docs
weight: 14
url: /zh/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) method

将包含数字字符串表示的指定字符串转换为等效的 16 位有符号整数。

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 用于转换的字符串。 |
| result | **int16_t**\& | 转换结果存放的 16 位有符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method

将包含数字字符串表示的指定字符串转换为等效的 16 位有符号整数，使用提供的格式信息和数字样式。

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 用于转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum 的值的按位组合，指定数字字符串表示的允许样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |
| result | **int16_t**\& | 转换结果存放的 16 位有符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## 另请参见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Int16](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)