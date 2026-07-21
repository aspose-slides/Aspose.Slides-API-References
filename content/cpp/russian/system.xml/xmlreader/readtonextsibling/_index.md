---
title: ReadToNextSibling()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает XmlReader к следующему элементу-соседу с указанным квалифицированным именем.
type: docs
weight: 924
url: /ru/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) метод


Перемещает [XmlReader](../) к следующему элементу-соседу с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Квалифицированное имя элемента-соседа, к которому вы хотите переместиться. |

### Возвращаемое значение

**true** если найден подходящий элемент-сосед; в противном случае **false**. Если подходящий элемент-сосед не найден, [XmlReader](../) позиционируется на закрывающем теге (значение [XmlReader::get_NodeType](../get_nodetype/) равно [XmlNodeType::EndElement](../../xmlnodetype/)) родительского элемента.

## XmlReader::ReadToNextSibling(String, String) метод


Перемещает [XmlReader](../) к следующему элементу-соседу с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента-соседа, к которому вы хотите переместиться. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён элемента-соседа, к которому вы хотите переместиться. |

### Возвращаемое значение

**true** если найден соответствующий элемент-сосед; иначе **false**. Если соответствующий элемент-сосед не найден, [XmlReader](../) позиционируется на закрывающем теге (значение [XmlReader::get_NodeType](../get_nodetype/) равно [XmlNodeType::EndElement](../../xmlnodetype/)) родительского элемента.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)