---
title: UInt32
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с беззнаковым 32-битным целым числом.
type: docs
weight: 1951
url: /ru/system/uint32/
---
## UInt32 struct

Содержит методы для работы с беззнаковым 32-битным целым числом.

```cpp
class UInt32
```

## Методы

| Метод | Описание |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую текстовое представление числа, в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую текстовое представление числа, в эквивалентное 32-битное беззнаковое целое, используя предоставленную информацию о форматировании. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую текстовое представление числа, в эквивалентное 32-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Преобразует указанную строку, содержащую текстовое представление числа, в эквивалентное 32-битное беззнаковое целое. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Преобразует указанную строку, содержащую текстовое представление числа, в эквивалентное 32-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)