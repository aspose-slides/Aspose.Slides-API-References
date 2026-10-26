---
title: ReadAttributeValue()
second_title: Aspose.Slides для C++ справка API
description: Разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity.
type: docs
weight: 430
url: /ru/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() метод

Parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Возвращаемое значение

**true** если есть узлы для возврата. **false** если читатель не находится на узле атрибута при первоначальном вызове или если все значения атрибутов уже прочитаны. Пустой атрибут, например, **misc=\"\"**, возвращает **true** с одним узлом, значение которого **[String::Empty](../../../system/string/empty/)**.

## См. также

* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)