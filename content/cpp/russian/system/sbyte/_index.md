---
title: SByte
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с 8-битным целым.
type: docs
weight: 1847
url: /ru/system/sbyte/
---
## SByte структура

Содержит методы для работы с 8-битным целым.

```cpp
class SByte
```

## Методы

| Method | Описание |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентный 8-битный знаковый целый. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентный 8-битный знаковый целый, используя предоставленную информацию о формате. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентный 8-битный знаковый целый, используя предоставленную информацию о формате и стиль числа. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентный 8-битный знаковый целый. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентный 8-битный знаковый целый, используя предоставленную информацию о формате и стиль числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Поля

| Field | Описание |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |

## См. также

* Применение [System](../)
* Библиотека [Aspose.Slides](../../)