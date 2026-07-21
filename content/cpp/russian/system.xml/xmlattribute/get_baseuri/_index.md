---
title: get_BaseURI()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает базовый униформный идентификатор ресурса (URI) узла.
type: docs
weight: 183
url: /ru/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() метод


Возвращает базовый униформный идентификатор ресурса (URI) узла.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Возвращаемое значение

Местоположение, из которого был загружен узел, или [String::Empty](../../../system/string/empty/), если у узла нет базового URI. Узлы [Attribute](../../../system/attribute/) имеют тот же базовый URI, что и их элемент-владелец. Если у атрибутного узла нет элемент-владельца, get_BaseURI возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlAttribute](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)