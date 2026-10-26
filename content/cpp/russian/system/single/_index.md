---
title: Single
second_title: Aspose.Slides для C++ справочника API
description: Содержит методы для работы с числом одинарной точности с плавающей запятой.
type: docs
weight: 1873
url: /ru/system/single/
---
## Одиночная структура

Содержит методы для работы с числом одинарной точности с плавающей запятой.

```cpp
class Single
```

## Методы

| Метод | Описание |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой, используя предоставленную информацию о форматировании. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой, используя предоставленную информацию о форматировании и стиль числа. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой, используя предоставленную информацию о форматировании и стиль числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Наименьшее положительное значение, превышающее ноль. |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |
| static constexpr [NaN](./nan/) | Значение, не являющееся числом. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Отрицательная бесконечность. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Положительная бесконечность. |

## Смотрите также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)