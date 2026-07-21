---
title: MoveToAttribute()
second_title: Aspose.Slides для C++ справочник API
description: Перемещается к атрибуту с указанным именем.
type: docs
weight: 508
url: /ru/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) метод

Перемещается к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция считывателя не меняется.

## XmlTextReader::MoveToAttribute(String, String) метод

Перемещается к атрибуту с указанным локальным именем и URI пространства имён.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция считывателя не меняется.

## XmlTextReader::MoveToAttribute(int32_t) метод

Перемещается к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)