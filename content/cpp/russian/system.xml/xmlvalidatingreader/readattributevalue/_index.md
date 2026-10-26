---
title: ReadAttributeValue()
second_title: Aspose.Slides для C++ справочник API
description: Разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity.
type: docs
weight: 508
url: /ru/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() метод

Parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Возвращаемое значение

**true** если есть узлы для возврата. **false** если читатель не находится на узле атрибута при первом вызове или если все значения атрибутов уже прочитаны. Пустой атрибут, например **misc=\"\"**, возвращает **true** с единственным узлом со значением [String::Empty](../../../system/string/empty/).

## Смотрите также

* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)