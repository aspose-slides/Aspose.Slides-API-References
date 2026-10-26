---
title: Double
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с числом двойной точности с плавающей запятой.
type: docs
weight: 1548
url: /ru/system/double/
---
## Double struct

Содержит методы для работы с числом двойной точности с плавающей запятой.

```cpp
class Double
```

## Методы

| Метод | Описание |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую символьное представление числа, в эквивалентное значение двойной точности с плавающей запятой. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую символьное представление числа, в эквивалентное значение двойной точности с плавающей запятой с использованием предоставленной информации о форматировании. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую символьное представление числа, в эквивалентное значение двойной точности с плавающей запятой с использованием предоставленной информации о форматировании и стиле числа. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Преобразует указанную строку, содержащую символьное представление числа, в эквивалентное значение двойной точности с плавающей запятой. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Преобразует указанную строку, содержащую символьное представление числа, в эквивалентное значение двойной точности с плавающей запятой с использованием предоставленной информации о форматировании и стиле числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Наименьшее положительное значение, большее нуля. |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |
| static constexpr [NaN](./nan/) | Значение, которое не является числом. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Отрицательная бесконечность. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Положительная бесконечность. |

## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)