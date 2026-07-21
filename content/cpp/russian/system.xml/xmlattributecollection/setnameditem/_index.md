---
title: SetNamedItem()
second_title: Aspose.Slides для C++ справочник API
description: "Добавляет XmlNode, используя результат XmlNode::get_Name."
type: docs
weight: 14
url: /ru/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) метод

Добавляет [XmlNode](../../xmlnode/) с помощью результата его [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Узел-атрибут, который будет храниться в этой коллекции. Позже узел будет доступен по имени узла. Если узел с таким именем уже присутствует в коллекции, он будет заменён новым; в противном случае узел будет добавлен в конец коллекции. |

### Возвращаемое значение

Если **node** заменяет существующий узел с тем же именем, возвращается старый узел; в противном случае возвращается добавленный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlAttributeCollection](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)