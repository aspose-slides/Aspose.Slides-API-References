---
title: MoveToContent()
second_title: Aspose.Slides для C++ справочная документация API
description: "Проверяет, является ли текущий узел узлом содержимого (текст без пробельных символов, CDATA, Element, EndElement, EntityReference или EndEntity). Если узел не является узлом содержимого, reader переходит к следующему узлу содержимого или к концу файла. Он пропускает узлы следующего типа: ProcessingInstruction, DocumentType, Comment, Whitespace или SignificantWhitespace."
type: docs
weight: 833
url: /ru/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() метод


Проверяет, является ли текущий узел содержимым (текст без пробельных символов, **CDATA**, **Element**, **EndElement**, **EntityReference** или **EndEntity**) узлом. Если узел не является узлом содержимого, reader переходит к следующему узлу содержимого или к концу файла. Он пропускает узлы следующего типа: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** или **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Возвращаемое значение

Значение [XmlReader::get_NodeType](../get_nodetype/) текущего узла, найденного методом, или [XmlNodeType::None](../../xmlnodetype/), если reader достиг конца входного потока.

## См. также

* Перечисление [XmlNodeType](../../xmlnodetype/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)