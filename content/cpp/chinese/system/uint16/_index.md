---
title: UInt16
second_title: Aspose.Slides for C++ API 参考
description: 包含用于处理无符号 16 位整数的方法。
type: docs
weight: 1938
url: /zh/system/uint16/
---
## UInt16 结构体

包含用于处理无符号 16 位整数的方法。

```cpp
class UInt16
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | 将指定的包含数字字符串表示形式的字符串转换为等效的 16 位无符号整数。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将指定的包含数字字符串表示形式的字符串转换为等效的 16 位无符号整数。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将指定的包含数字字符串表示形式的字符串转换为等效的 16 位无符号整数。 |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | 将指定的包含数字字符串表示形式的字符串转换为等效的 16 位无符号整数。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | 使用提供的格式信息和数字样式，将指定的包含数字字符串表示形式的字符串转换为等效的 16 位无符号整数。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |

## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 可能的最大值。 |
| static constexpr [MinValue](./minvalue/) | 可能的最小值。 |

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)