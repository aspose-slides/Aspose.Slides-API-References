---
title: GetNamedItem()
second_title: Справка по API Aspose.Slides для C++
description: Получает объект XmlNode, указанный по имени.
type: docs
weight: 14
url: /ru/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) метод

Получает [XmlNode](../../xmlnode/) по имени.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя узла для извлечения. Сравнивается со значением [XmlNode::get_Name](../../xmlnode/get_name/) соответствующего узла. |

### Возвращаемое значение

Объект [XmlNode](../../xmlnode/) с указанным именем или **nullptr**, если соответствующий узел не найден.

## XmlNamedNodeMap::GetNamedItem(String, String) метод

Получает узел со значениями [XmlNode::get_LocalName](../../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/), соответствующими параметрам.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя узла для извлечения. |
| namespaceURI | [String](../../../system/string/) | Универсальный идентификатор ресурса (URI) пространства имён узла для извлечения. |

### Возвращаемое значение

Объект [XmlNode](../../xmlnode/) с совпадающим локальным именем и URI пространства имён или **nullptr**, если соответствующий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [String](../../../system/string/)
* Класс [XmlNamedNodeMap](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)