---
title: UInt64
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с беззнаковым 64-битным целым числом.
type: docs
weight: 1964
url: /ru/system/uint64/
---
## UInt64 struct

Содержит методы для работы с беззнаковым 64-битным целым числом.

```cpp
class UInt64
```

## Методы

| Метод | Описание |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое, используя предоставленную информацию о форматировании. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое, используя предоставленную информацию о форматировании и стиль числа. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое, используя предоставленную информацию о форматировании и стиль числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |

## См. также

* Пространство имён [System](../)
* Library [Aspose.Slides](../../)