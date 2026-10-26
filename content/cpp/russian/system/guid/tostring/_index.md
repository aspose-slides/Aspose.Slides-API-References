---
title: ToString()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует GUID, представленный текущим объектом, в его строковое представление.
type: docs
weight: 79
url: /ru/system/guid/tostring/
---
## Guid::ToString() const метод

Преобразует GUID, представленный текущим объектом, в его строковое представление.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const метод

Преобразует GUID, представленный текущим объектом, в его строковое представление, используя указанный строковый формат.

```cpp
String System::Guid::ToString(const String &format) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Формат, который следует использовать |

### Возвращаемое значение

Строковое представление значения GUID, представленного текущим объектом

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const метод

Преобразует GUID, представленный текущим объектом, в его строковое представление, используя указанный строковый формат и культуру.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Формат, который следует использовать |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, которую следует использовать |

### Возвращаемое значение

Строковое представление значения GUID, представленного текущим объектом

## См. также

* Тип-определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Guid](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)