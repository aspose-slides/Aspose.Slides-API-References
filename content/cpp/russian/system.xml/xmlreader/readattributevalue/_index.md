---
title: ReadAttributeValue()
second_title: Aspose.Slides для C++ справка API
description: При переопределении в производном классе разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity.
type: docs
weight: 677
url: /ru/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() метод

When overridden in a derived class, parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Возвращаемое значение

**true** если есть узлы для возврата. **false** если ридер не находится на узле атрибута при первоначальном вызове или если все значения атрибутов уже прочитаны. Пустой атрибут, например, **misc=\"\"**, возвращает **true** с единственным узлом со значением [String::Empty](../../../system/string/empty/).

## См. также

* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)