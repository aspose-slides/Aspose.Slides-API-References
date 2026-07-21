---
title: TryParse()
second_title: Aspose.Slides для C++ API Reference
description: Преобразует указанное строковое представление значения даты и времени в эквивалентный объект DateTime.
type: docs
weight: 885
url: /ru/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) метод

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../).

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени, которое нужно преобразовать. |
| result | [DateTime](../)\& | Выходной аргумент, который при успешном преобразовании содержит результат преобразования. |

### Возвращаемое значение

True, если преобразование успешно, иначе — false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) метод

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../) с использованием указанных культуры-специфических параметров форматирования и стиля.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени, которое нужно преобразовать. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий культура-специфическую информацию о формате. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Побитовое сочетание значений перечисления, которое предоставляет дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании из **s** в объект [DateTime](../). |
| result | [DateTime](../)\& | Выходной аргумент, который при успешном преобразовании содержит результат преобразования. |

### Возвращаемое значение

True, если преобразование успешно, иначе — false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) метод

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) метод

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) метод

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## См. также

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)