---
title: ReadAttributeValue()
second_title: Справочник API Aspose.Slides для C++
description: Разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity.
type: docs
weight: 560
url: /ru/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() метод

Разбирает значение атрибута в один или несколько узлов **[Text](../../../system.text/)**, **EntityReference** или **EndEntity**.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Возвращаемое значение

**true** если есть узлы для возврата. **false** если читатель не находится на узле атрибута при первоначальном вызове или если все значения атрибутов уже прочитаны. Пустой атрибут, например, **misc=""**, возвращает **true** с единственным узлом со значением [String::Empty](../../../system/string/empty/).

## Смотрите также

* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)