---
title: GetElementsByTagName()
second_title: Aspose.Slides для C++ справки API
description: Возвращает XmlNodeList, содержащий список всех дочерних элементов, соответствующих указанному имени.
type: docs
weight: 443
url: /ru/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) метод

Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанному имени.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя для сопоставления. Оно сравнивается со значением **get_Name** соответствующего узла. Специальное значение **\"*\"** соответствует всем тегам. |

### Возвращаемое значение

Объект [XmlNodeList](../../xmlnodelist/), содержащий список всех подходящих узлов. Если ни один узел не соответствует **name**, возвращаемая коллекция будет пустой.

## XmlDocument::GetElementsByTagName(String, String) метод

Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанным [XmlDocument::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | LocalName для сопоставления. Специальное значение **\"*\"** соответствует всем тегам. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI для сопоставления. |

### Возвращаемое значение

Объект [XmlNodeList](../../xmlnodelist/), содержащий список всех подходящих узлов. Если ни один узел не соответствует указанным **localName** и **namespaceURI**, возвращаемая коллекция будет пустой.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNodeList](../../xmlnodelist/)
* Класс [String](../../../system/string/)
* Класс [XmlDocument](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)