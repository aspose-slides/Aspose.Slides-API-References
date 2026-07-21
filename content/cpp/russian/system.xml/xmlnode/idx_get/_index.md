---
title: idx_get()
second_title: Aspose.Slides для C++ справочник API
description: "Возвращает первый дочерний элемент с указанным XmlNode::get_Name."
type: docs
weight: 586
url: /ru/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) метод

Возвращает первый дочерний элемент с указанным [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя элемента, которое нужно получить. |

### Возвращаемое значение

Первый [XmlElement](../../xmlelement/), который соответствует указанному имени. Возвращает **nullptr**, если совпадения не найдено.

## XmlNode::idx_get(String, String) метод

Возвращает первый дочерний элемент с указанными значениями [XmlNode::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Локальное имя элемента. |
| ns | [String](../../../system/string/) | URI пространства имен элемента. |

### Возвращаемое значение

Первый [XmlElement](../../xmlelement/) с совпадающими **localname** и **ns**. Возвращает **nullptr**, если совпадения не найдено.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)