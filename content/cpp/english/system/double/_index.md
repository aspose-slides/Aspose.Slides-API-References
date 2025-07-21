---
title: Double
second_title: Aspose.Slides for C++ API Reference
description: Contains methods to work with the double-precision floating-point number.
type: docs
weight: 1483
url: /system/double/
---
## Double struct


Contains methods to work with the double-precision floating-point number.

```cpp
class Double
```

## Methods

| Method | Description |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Smallest positive value that is greater than zero. |
| static constexpr [MaxValue](./maxvalue/) | Largest possible value. |
| static constexpr [MinValue](./minvalue/) | Smallest possible value. |
| static constexpr [NaN](./nan/) | Value that is not a number. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negative infinity. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positive infinity. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)