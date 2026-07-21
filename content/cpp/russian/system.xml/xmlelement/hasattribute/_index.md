---
title: HasAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, имеет ли текущий узел атрибут с указанным именем.
type: docs
weight: 300
url: /ru/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) метод

Определяет, имеет ли текущий узел атрибут с указанным именем.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя атрибута, который требуется найти. Это квалифицированное имя. Сравнивается со значением **get_Name** соответствующего узла. |

### Возвращаемое значение

**true** если текущий узел содержит указанный атрибут; в противном случае **false**.

## XmlElement::HasAttribute(String, String) метод

Определяет, имеет ли текущий узел атрибут с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута, который требуется найти. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута, который требуется найти. |

### Возвращаемое значение

**true** если текущий узел содержит указанный атрибут; в противном случае **false**.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)