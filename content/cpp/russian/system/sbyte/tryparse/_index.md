---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое.
type: docs
weight: 14
url: /ru/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **int8_t**\& | Ссылка на переменную 8-битного знакового целого, в которой помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование завершилось успешно, иначе — false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, которое задаёт разрешённый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **int8_t**\& | Ссылка на переменную 8-битного знакового целого, в которой помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование завершилось успешно, иначе — false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) метод

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) метод

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) метод

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)