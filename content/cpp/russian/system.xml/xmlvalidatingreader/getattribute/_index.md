---
title: GetAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение атрибута с указанным именем.
type: docs
weight: 443
url: /ru/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) метод


Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается.

## XmlValidatingReader::GetAttribute(String, String) метод


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается. Этот метод не передвигает читатель.

## XmlValidatingReader::GetAttribute(int32_t) метод


Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### Возвращаемое значение

Значение указанного атрибута.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)