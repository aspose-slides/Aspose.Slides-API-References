---
title: Int16
second_title: Aspose.Slides C++ API 参考
description: 包含用于处理 16 位整数的方法。
type: docs
weight: 1015
url: /zh/system/int16/
---
## Int16 类


包含用于处理 16 位整数的方法。

```cpp
class Int16
```

## 方法

| 方法 | 说明 |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | 将指定的包含数字字符串表示的字符串转换为等效的 16 位有符号整数。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将指定的包含数字字符串表示的字符串转换为等效的 16 位有符号整数。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将指定的包含数字字符串表示的字符串转换为等效的 16 位有符号整数。 |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | 将指定的包含数字字符串表示的字符串转换为等效的 16 位有符号整数。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | 使用提供的格式信息和数字样式，将指定的包含数字字符串表示的字符串转换为等效的 16 位有符号整数。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## 字段

| 字段 | 说明 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 可能的最大值。 |
| static constexpr [MinValue](./minvalue/) | 可能的最小值。 |

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)