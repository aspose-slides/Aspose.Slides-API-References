---
title: ToString()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает строковое представление временного интервала, представленного текущим объектом.
type: docs
weight: 261
url: /ru/system/timespan/tostring/
---
## TimeSpan::ToString() const метод

Возвращает строковое представление временного интервала, представленного текущим объектом.

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const метод

Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат.

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const метод

Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат и поставщик формата.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const метод




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const метод




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const метод




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [TimeSpan](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)