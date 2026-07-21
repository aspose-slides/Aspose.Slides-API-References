---
title: ToDateTimeOffset()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует предоставленный String в эквивалентный DateTimeOffset.
type: docs
weight: 430
url: /ru/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) метод

Преобразует предоставленный [String](../../../system/string/) в эквивалентный [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. Строка должна соответствовать подмножеству рекомендации W3C для типа XML dateTime. Для получения дополнительной информации см. раздел [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) спецификации XML [Schema](../../../system.xml.schema/). |

### Возвращаемое значение

Эквивалент [DateTimeOffset](../../../system/datetimeoffset/) предоставленной строки.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) метод

Преобразует предоставленный [String](../../../system/string/) в эквивалентный [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. |
| format | const [String](../../../system/string/)\& | Формат, из которого **s** преобразуется. Параметр format может быть любой подсеткой рекомендации W3C для типа XML dateTime. Для получения дополнительной информации см. раздел [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) спецификации XML [Schema](../../../system.xml.schema/). Строка **s** проверяется в соответствии с этим форматом. |

### Возвращаемое значение

Эквивалент [DateTimeOffset](../../../system/datetimeoffset/) предоставленной строки.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) метод

Преобразует предоставленный [String](../../../system/string/) в эквивалентный [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Массив форматов, из которых может быть преобразован **s**. Каждый формат в **formats** может быть любой подсеткой рекомендации W3C для типа XML dateTime. Для получения дополнительной информации см. раздел [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) спецификации XML [Schema](../../../system.xml.schema/). Строка **s** проверяется в соответствии с одним из этих форматов. |

### Возвращаемое значение

Эквивалент [DateTimeOffset](../../../system/datetimeoffset/) предоставленной строки.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [DateTimeOffset](../../../system/datetimeoffset/)
* Класс [String](../../../system/string/)
* Класс [XmlConvert](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)