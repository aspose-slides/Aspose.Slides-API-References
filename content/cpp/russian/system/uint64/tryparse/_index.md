---
title: TryParse()
second_title: Aspose.Slides для C++ — справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное беззнаковое целое.
type: docs
weight: 14
url: /ru/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное беззнаковое целое.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **uint64_t**\& | Ссылка на переменную 64-битного беззнакового целого, в которую помещается результат преобразования. |

### Return Value

True, если преобразование выполнено успешно, иначе — false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое объединение значений перечисления NumberStyles, указывающее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **uint64_t**\& | Ссылка на переменную 64-битного беззнакового целого, в которую помещается результат преобразования. |

### Return Value

True, если преобразование выполнено успешно, иначе — false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) метод

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) метод

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) метод

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)