---
title: ToDateTime()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует строку в эквивалент DateTime.
type: docs
weight: 417
url: /ru/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) метод


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. |

### Возвращаемое значение

Эквивалент [DateTime](../../../system/datetime/) строки.

## XmlConvert::ToDateTime(const String\&, const String\&) метод


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. |
| format | const [String](../../../system/string/)\& | Структура формата, применяемая к преобразованному [DateTime](../../../system/datetime/). Допустимые форматы включают "yyyy-MM-ddTHH:mm:sszzzzzz" и их подмножества. Строка проверяется на соответствие этому формату. |

### Возвращаемое значение

Эквивалент [DateTime](../../../system/datetime/) строки.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) метод


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Строка для преобразования. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Массив, содержащий структуры форматов, применяемые к преобразованному [DateTime](../../../system/datetime/). Допустимые форматы включают "yyyy-MM-ddTHH:mm:sszzzzzz" и их подмножества. |

### Возвращаемое значение

Эквивалент [DateTime](../../../system/datetime/) строки.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) метод


Преобразует [String](../../../system/string/) в [DateTime](../../../system/datetime/) с использованием указанного XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) значение для преобразования. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Одно из значений перечисления, определяющих, следует ли преобразовать дату во местное время или сохранить её как всемирное координированное время (UTC), если это дата в формате UTC. |

### Возвращаемое значение

Эквивалент [DateTime](../../../system/datetime/) [String](../../../system/string/).

## См. также

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [DateTime](../../../system/datetime/)
* Класс [String](../../../system/string/)
* Класс [XmlConvert](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)