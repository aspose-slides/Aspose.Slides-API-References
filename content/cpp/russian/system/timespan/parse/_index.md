---
title: Parse()
second_title: Aspose.Slides для C++: справочник API
description: Преобразует строку в эквивалентный объект TimeSpan.
type: docs
weight: 534
url: /ru/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) метод


Преобразует строку в эквивалентный объект [TimeSpan](../).

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |

### Возвращаемое значение

Интервал времени, соответствующий строке.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует строку в эквивалентный объект [TimeSpan](../) с использованием указанного поставщика формата.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата, предоставляющий информацию о форматировании, зависящую от культуры. |

### Возвращаемое значение

Интервал времени, соответствующий строке.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) метод




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) метод




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)