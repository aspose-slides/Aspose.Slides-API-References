---
title: idx_get()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает узел по заданному индексу.
type: docs
weight: 40
url: /ru/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) метод

Возвращает узел по заданному индексу.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Нулевой индекс в списке узлов. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) с указанным индексом в коллекции. Если индекс больше или равен количеству узлов в списке, возвращается **nullptr**.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNodeList](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)