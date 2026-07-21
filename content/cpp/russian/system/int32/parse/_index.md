---
title: Parse()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное знаковое целое.
type: docs
weight: 1
url: /ru/system/int32/parse/
---
## Int32::Parse(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное знаковое целое.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |

### Return Value

32-разрядное знаковое целое, равное числу, представленному в указанной строке.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное знаковое целое, используя предоставленную информацию о формате.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Return Value

32-разрядное знаковое целое, равное числу, представленному в указанной строке.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) метод

```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-разрядное знаковое целое, используя предоставленную информацию о формате и стиль числа.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, указывающее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Return Value

32-разрядное знаковое целое, равное числу, представленному в указанной строке.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) метод

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) метод

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) метод

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Int32](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Класс [ReadOnlySpan](../../readonlyspan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)