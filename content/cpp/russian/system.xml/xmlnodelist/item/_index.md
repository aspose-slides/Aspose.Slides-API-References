---
title: Item()
second_title: Aspose.Slides для C++ справочника API
description: Получает узел по заданному индексу.
type: docs
weight: 14
url: /ru/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) метод

Получает узел по заданному индексу.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс в списке узлов. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) с указанным индексом в коллекции. Если **index** больше или равен количеству узлов в списке, возвращается **nullptr**.

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNodeList](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)