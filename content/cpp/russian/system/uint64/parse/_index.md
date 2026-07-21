---
title: Parse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное беззнаковое целое.
type: docs
weight: 1
url: /ru/system/uint64/parse/
---
## UInt64::Parse(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-разрядное беззнаковое целое.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |

### Возвращаемое значение

64-разрядное беззнаковое целое, равное числу, представленному указанной строкой.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-разрядное беззнаковое целое, используя предоставленную информацию о форматировании.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

64-разрядное беззнаковое целое, равное числу, представленному указанной строкой.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-разрядное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, указывающее разрешённый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

64-разрядное беззнаковое целое, равное числу, представленному указанной строкой.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) метод

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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