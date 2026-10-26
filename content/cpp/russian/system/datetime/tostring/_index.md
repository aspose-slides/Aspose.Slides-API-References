---
title: ToString()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя правила форматирования, определённые текущей культурой.
type: docs
weight: 482
url: /ru/system/datetime/tostring/
---
## DateTime::ToString() const метод

Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя правила форматирования, определённые текущей культурой.

```cpp
String System::DateTime::ToString() const
```

### Возвращаемое значение

Строковое представление значения, представленного текущим объектом

## DateTime::ToString(const String\&) const метод

Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанный формат и правила форматирования, определённые текущей культурой.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Строка формата |

### Возвращаемое значение

Строковое представление значения, представленного текущим объектом, отформатированное согласно формату, определённому **format**, и текущей культуре.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const метод

Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанную информацию о формате.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект, представляющий информацию о формате |

### Возвращаемое значение

Строковое представление значения, представленного текущим объектом, отформатированное согласно информации о формате, предоставленной **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const метод

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const метод

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const метод

```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const метод

Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанную информацию о формате.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Строка формата |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект, представляющий информацию о формате |

### Возвращаемое значение

Строковое представление значения, представленного текущим объектом, отформатированное согласно информации о формате, предоставленной **provider**, и строке формата **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const метод

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const метод

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const метод

```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [DateTime](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)