---
title: GetElementsByTagName()
second_title: Справочник API Aspose.Slides для C++
description: "Возвращает XmlNodeList, содержащий список всех дочерних элементов, которые соответствуют указанному XmlElement::get_Name."
type: docs
weight: 287
url: /ru/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) метод

Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, которые соответствуют указанному [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Тег name для сопоставления. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. Символ звёздочка (*) является специальным значением, которое сопоставляется со всеми тегами. |

### Возвращаемое значение

[XmlNodeList](../../xmlnodelist/), содержащий список всех соответствующих узлов. Список будет пустым, если соответствующих узлов нет.

## XmlElement::GetElementsByTagName(String, String) метод

Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, которые соответствуют указанным значениям [XmlElement::get_LocalName](../get_localname/) и [XmlElement::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя для сопоставления. Символ звёздочка (*) является специальным значением, которое сопоставляется со всеми тегами. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён для сопоставления. |

### Возвращаемое значение

[XmlNodeList](../../xmlnodelist/), содержащий список всех соответствующих узлов. Список будет пустым, если соответствующих узлов нет.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNodeList](../../xmlnodelist/)
* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)