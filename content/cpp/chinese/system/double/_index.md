---
title: Double
second_title: Aspose.Slides C++ API 参考
description: 包含用于处理双精度浮点数的方法。
type: docs
weight: 1548
url: /zh/system/double/
---
## 双精度结构

包含用于处理双精度浮点数的方法。

```cpp
class Double
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值，使用提供的格式信息。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值，使用提供的格式信息和数字样式。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值，使用提供的格式信息和数字样式。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 大于零的最小正值。 |
| static constexpr [MaxValue](./maxvalue/) | 最大可能值。 |
| static constexpr [MinValue](./minvalue/) | 最小可能值。 |
| static constexpr [NaN](./nan/) | 非数字值。 |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 负无穷大。 |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 正无穷大。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)