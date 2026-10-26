---
title: ParseExact()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует строку в эквивалентный объект TimeSpan, используя указанные форматы, провайдер форматов и стили.
type: docs
weight: 547
url: /ru/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) метод

Преобразует строку в эквивалентный объект [TimeSpan](../) с использованием указанных форматов, поставщика форматов и стилей.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) строк формата. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Определяет элементы, которые могут присутствовать во входной строке. |

### Возвращаемое значение

Временной интервал, соответствующий строке.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) метод

Преобразует строку в эквивалентный объект [TimeSpan](../) с использованием указанного формата, поставщика форматов и стилей.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |
| format | const [String](../../string/)\& | Стандартная или пользовательская строка формата. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов, предоставляющий информацию о форматировании, специфичную для культуры. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Определяет элементы, которые могут присутствовать во входной строке. |

### Возвращаемое значение

Временной интервал, соответствующий строке.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) метод

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Смотрите также

* Перечисление [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Типовое определение [ArrayPtr](../../arrayptr/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [TimeSpan](../)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)