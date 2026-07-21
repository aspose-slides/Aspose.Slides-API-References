---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное беззнаковое целое.
type: docs
weight: 14
url: /ru/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное беззнаковое целое.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **uint32_t**\& | Ссылка на 32-разрядную беззнаковую переменную целого, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование выполнено успешно, иначе — false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, определяющее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **uint32_t**\& | Ссылка на 32-разрядную беззнаковую переменную целого, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование выполнено успешно, иначе — false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) метод

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) метод

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) метод

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Смотрите также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Структура [UInt32](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)