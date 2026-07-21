---
title: ReadSubtree()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает новый экземпляр XmlReader, который можно использовать для чтения текущего узла и всех его потомков.
type: docs
weight: 963
url: /ru/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() метод

Возвращает новый экземпляр [XmlReader](../), который можно использовать для чтения текущего узла и всех его потомков.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Возвращаемое значение

Новый экземпляр XML reader, установленный на [ReadState::Initial](../../readstate/). Вызов метода [XmlReader::Read](../read/) позиционирует новый читатель на узле, который был текущим до вызова метода [XmlReader::ReadSubtree](./).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)