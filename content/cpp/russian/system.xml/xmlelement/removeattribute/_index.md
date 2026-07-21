---
title: RemoveAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет атрибут по имени.
type: docs
weight: 235
url: /ru/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) метод

Удаляет атрибут по имени.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя атрибута, который нужно удалить. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. |

## XmlElement::RemoveAttribute(String, String) метод

Удаляет атрибут с указанным локальным именем и URI пространства имён. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута, который нужно удалить. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута, который нужно удалить. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)