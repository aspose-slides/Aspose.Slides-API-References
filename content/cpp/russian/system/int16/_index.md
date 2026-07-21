---
title: Int16
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с 16-разрядным целым числом.
type: docs
weight: 1015
url: /ru/system/int16/
---
## Int16 класс


Содержит методы для работы с 16-разрядным целым числом.

```cpp
class Int16
```

## Методы

| Метод | Описание |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое, используя предоставленную информацию о формате. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое, используя предоставленную информацию о формате и стиль числа. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое, используя предоставленную информацию о формате и стиль числа. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)