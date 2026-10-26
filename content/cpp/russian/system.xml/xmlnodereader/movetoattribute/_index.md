---
title: MoveToAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Переходит к атрибуту с указанным именем.
type: docs
weight: 300
url: /ru/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) метод


Переходит к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Квалифицированное имя атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция читателя не меняется.

## XmlNodeReader::MoveToAttribute(String, String) метод


Переходит к атрибуту с указанным локальным именем и URI пространства имён.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

**true** если атрибут найден; в противном случае **false**. Если **false**, позиция читателя не меняется.

## XmlNodeReader::MoveToAttribute(int32_t) метод


Переходит к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeIndex | **int32_t** | Индекс атрибута. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)