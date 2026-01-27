---
title: Single
second_title: Aspose.Slides for C++ API Reference
description: Contains methods to work with the single-precision floating-point number.
type: docs
weight: 1847
url: /system/single/
---
## Single struct


Contains methods to work with the single-precision floating-point number.

```cpp
class Single
```

## Methods

| Method | Description |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |
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