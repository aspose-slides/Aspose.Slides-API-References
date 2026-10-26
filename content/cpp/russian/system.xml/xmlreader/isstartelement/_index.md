---
title: IsStartElement()
second_title: Справочник API Aspose.Slides для C++
description: "Вызывает XmlReader::MoveToContent и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента."
type: docs
weight: 885
url: /ru/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() метод

Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Возвращаемое значение

**true** если [XmlReader::MoveToContent](../movetocontent/) находит стартовый тег или тег пустого элемента; **false** если найден тип узла, отличный от [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) метод

Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента и соответствует ли значение [XmlReader::get_Name](../get_name/) найденного элемента заданному аргументу.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Строка, сопоставляемая со значением **Name** найденного элемента. |

### Возвращаемое значение

**true** если полученный узел является элементом и значение **Name** соответствует указанной строке. **false** если найден тип узла, отличный от [XmlNodeType::Element](../../xmlnodetype/) или значение **Name** элемента не соответствует указанной строке.

## XmlReader::IsStartElement(String, String) метод

Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента и соответствуют ли значения [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) найденного элемента заданным строкам.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Строка, сопоставляемая со значением **LocalName** найденного элемента. |
| ns | [String](../../../system/string/) | Строка, сопоставляемая со значением **NamespaceURI** найденного элемента. |

### Возвращаемое значение

**true** если полученный узел является элементом. **false** если найден тип узла, отличный от [XmlNodeType::Element](../../xmlnodetype/) или значения **LocalName** и **NamespaceURI** элемента не соответствуют указанным строкам.

## См. также

* Класс [XmlReader](../)
* Класс [String](../../../system/string/)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)