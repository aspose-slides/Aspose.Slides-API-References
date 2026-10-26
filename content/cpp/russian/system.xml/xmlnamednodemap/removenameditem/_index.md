---
title: RemoveNamedItem()
second_title: Aspose.Slides для C++ API Reference
description: Удаляет узел из XmlNamedNodeMap.
type: docs
weight: 40
url: /ru/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) метод

Удаляет узел из [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя удаляемого узла. Имя сравнивается со значением [XmlNode::get_Name](../../xmlnode/get_name/) соответствующего узла. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) удалённый из этого [XmlNamedNodeMap](../) или **nullptr**, если соответствующий узел не найден.

## XmlNamedNodeMap::RemoveNamedItem(String, String) метод

Удаляет узел с совпадающими значениями [XmlNode::get_LocalName](../../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя удаляемого узла. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён удаляемого узла. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) удалён или **nullptr**, если соответствующий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [String](../../../system/string/)
* Класс [XmlNamedNodeMap](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)