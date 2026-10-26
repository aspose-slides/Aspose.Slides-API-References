---
title: SetNamedItem()
second_title: Aspose.Slides для C++ справочник API
description: "Добавляет XmlNode, используя его значение XmlNode::get_Name."
type: docs
weight: 27
url: /ru/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) метод

Добавляет [XmlNode](../../xmlnode/), используя его значение [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Объект [XmlNode](../../xmlnode/) для сохранения в [XmlNamedNodeMap](../). Если узел с таким именем уже присутствует в карте, он заменяется новым. |

### Возвращаемое значение

Если **node** заменяет существующий узел с тем же именем, возвращается старый узел; иначе возвращается **nullptr**.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNamedNodeMap](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)