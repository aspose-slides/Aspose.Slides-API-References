---
title: Parse()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное знаковое целое.
type: docs
weight: 1
url: /ru/system/int64/parse/
---
## Int64::Parse(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное знаковое целое.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |

### Возвращаемое значение

64-битное знаковое целое, равное числу, представленному в указанной строке.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное знаковое целое, используя предоставленную информацию о форматировании.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

64-битное знаковое целое, равное числу, представленному в указанной строке.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) метод




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, определяющее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

64-битное знаковое целое, равное числу, представленному в указанной строке.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)