---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует строку в эквивалентный объект TimeSpan и возвращает результат преобразования.
type: docs
weight: 560
url: /ru/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) метод


Преобразует строку в эквивалентный объект [TimeSpan](../) и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |
| result | [TimeSpan](../)\& | Интервал времени, соответствующий строке. |

### Возвращаемое значение

True если строка была успешно преобразована; иначе — false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) метод


Преобразует строку в эквивалентный объект [TimeSpan](../) с использованием указанного поставщика формата и возвращает результат преобразования.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | Входная строка. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата, который предоставляет сведения о форматировании, специфичные для культуры. |
| result | [TimeSpan](../)\& | Интервал времени, соответствующий строке. |

### Возвращаемое значение

True если строка была успешно преобразована; иначе — false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) метод




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) метод




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) метод




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)