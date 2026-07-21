---
title: GetAttribute()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение атрибута с указанным именем.
type: docs
weight: 287
url: /ru/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) метод

Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается.

## XmlNodeReader::GetAttribute(String, String) метод

Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается.

## XmlNodeReader::GetAttribute(int32_t) метод

Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeIndex | **int32_t** | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### Возвращаемое значение

Значение указанного атрибута.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)