---
title: TryParse()
second_title: Справка по API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное беззнаковое целое.
type: docs
weight: 14
url: /ru/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное беззнаковое целое.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **uint16_t**\& | Ссылка на переменную беззнакового 16-битного целого, в которую помещается результат преобразования. |

### Возвращаемое значение

True если преобразование удалось, иначе — false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовая комбинация значений перечисления NumberStyles, определяющая допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **uint16_t**\& | Ссылка на переменную беззнакового 16-битного целого, в которую помещается результат преобразования. |

### Возвращаемое значение

True если преобразование удалось, иначе — false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) метод




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) метод




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) метод




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Структура [UInt16](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)