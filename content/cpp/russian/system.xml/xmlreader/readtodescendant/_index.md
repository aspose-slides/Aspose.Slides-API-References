---
title: ReadToDescendant()
second_title: Aspose.Slides для C++ справочник API
description: Перемещает XmlReader к следующему дочернему элементу с указанным квалифицированным именем.
type: docs
weight: 911
url: /ru/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) метод

Перемещает [XmlReader](../) к следующему дочернему элементу с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Квалифицированное имя элемента, к которому вы хотите перейти. |

### Возвращаемое значение

**true** если найден подходящий дочерний элемент; в противном случае **false**. Если подходящий дочерний элемент не найден, [XmlReader](../) позиционируется на закрывающий тег (значение [XmlReader::get_NodeType](../get_nodetype/) равно [XmlNodeType::EndElement](../../xmlnodetype/)) элемента. Если [XmlReader](../) не позиционируется на элементе, когда вызывается [XmlReader::ReadToDescendant(String)](./), этот метод возвращает **false** и позиция [XmlReader](../) не изменяется.

## XmlReader::ReadToDescendant(String, String) метод

Перемещает [XmlReader](../) к следующему дочернему элементу с указанным локальным именем и URI пространства имен.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента, к которому вы хотите перейти. |
| namespaceURI | [String](../../../system/string/) | URI пространства имен элемента, к которому вы хотите перейти. |

### Возвращаемое значение

**true** если найден подходящий дочерний элемент; в противном случае **false**. Если подходящий дочерний элемент не найден, [XmlReader](../) позиционируется на закрывающий тег (значение [XmlReader::get_NodeType](../get_nodetype/) равно [XmlNodeType::EndElement](../../xmlnodetype/)) элемента. Если [XmlReader](../) не позиционируется на элементе, когда вызывается [XmlReader::ReadToDescendant(String,String)](./), этот метод возвращает **false** и позиция [XmlReader](../) не изменяется.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)