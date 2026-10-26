---
title: MoveToAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Перемещается к атрибуту с указанным именем.
type: docs
weight: 456
url: /ru/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) метод

Перемещается к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция чтения не меняется.

## XmlValidatingReader::MoveToAttribute(String, String) метод

Перемещается к атрибуту с указанным локальным именем и URI пространства имён.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция чтения не меняется.

## XmlValidatingReader::MoveToAttribute(int32_t) метод

Перемещается к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)