---
title: TryParse()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-разрядное знаковое целое.
type: docs
weight: 14
url: /ru/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) method

Преобразует указанный строковый объект, содержащий строковое представление числа, в эквивалентное 64-разрядное знаковое целое.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **int64_t**\& | Ссылка на 64-разрядную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование прошло успешно, иначе — false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method

Преобразует указанный строковый объект, содержащий строковое представление числа, в эквивалентное 64-разрядное знаковое целое, используя предоставленную информацию о формате и стиль числа.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, указывающая допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий сведения о строковом формате. |
| result | **int64_t**\& | Ссылка на 64-разрядную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование прошло успешно, иначе — false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Смотрите также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Int64](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)