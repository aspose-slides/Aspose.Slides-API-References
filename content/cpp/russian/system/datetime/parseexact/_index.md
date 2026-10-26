---
title: ParseExact()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное строковое представление значения даты и времени в эквивалентный объект DateTime, используя указанный формат и информацию о формате, специфичную для культуры. Формат строкового представления должен точно соответствовать указанному формату. Выбрасывает исключение, если преобразование не удалось.
type: docs
weight: 872
url: /ru/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод

Преобразует заданное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанный формат и информацию о формате, специфичную для культуры. Формат строкового представления должен точно соответствовать указанному формату. Выбрасывает исключение, если преобразование не удалось.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |
| format | const [String](../../string/)\& | Строковый формат. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий информацию о формате, специфичную для культуры. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Битовое сочетание значений перечисления, которое предоставляет дополнительную информацию о **s**, о стилистических элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |

### Возвращаемое значение

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное значению, представленному указанной строкой.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод

Преобразует заданное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанные форматы, информацию о формате, специфичную для культуры, и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. Выбрасывает исключение, если преобразование не удалось.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Массив строковых форматов. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий информацию о формате, специфичную для культуры. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Битовое сочетание значений перечисления, которое предоставляет дополнительную информацию о **s**, о стилистических элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |

### Возвращаемое значение

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное значению, представленному указанной строкой.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) метод

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## См. также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Типовое определение [ArrayPtr](../../arrayptr/)
* Класс [DateTime](../)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)