---
title: ReadInnerXml()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе читает всё содержимое, включая разметку, как строку.
type: docs
weight: 937
url: /ru/system.xml/xmlreader/readinnerxml/
---
## XmlReader::ReadInnerXml() метод

When overridden in a derived class, reads all the content, including markup, as a string.

```cpp
virtual String System::Xml::XmlReader::ReadInnerXml()
```

### Возвращаемое значение

All the XML content, including markup, in the current node. If the current node has no children, an empty string is returned. If the current node is neither an element nor attribute, an empty string is returned.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)