---
title: GetAttribute()
second_title: Aspose.Slides для C++ API Справка
description: Возвращает значение атрибута с указанным именем.
type: docs
weight: 495
url: /ru/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) метод

Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Квалифицированное имя атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается.

## XmlTextReader::GetAttribute(String, String) метод

Возвращает значение атрибута с указанным локальным именем и URI пространства имен.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имен атрибута. |

### Возвращаемое значение

Значение указанного атрибута. Если атрибут не найден, **nullptr** возвращается. Этот метод не перемещает считыватель.

## XmlTextReader::GetAttribute(int32_t) метод

Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### Возвращаемое значение

Значение указанного атрибута.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlTextReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)