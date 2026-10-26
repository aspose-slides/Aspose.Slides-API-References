---
title: GetAttributeNode()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает XmlAttribute с указанным именем.
type: docs
weight: 248
url: /ru/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) метод


Возвращает [XmlAttribute](../../xmlattribute/) с указанным именем.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя атрибута, который нужно получить. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. |

### Return Value

Указанный [XmlAttribute](../../xmlattribute/) или **nullptr**, если соответствующий атрибут не найден.

## XmlElement::GetAttributeNode(String, String) метод


Возвращает [XmlAttribute](../../xmlattribute/) с указанным локальным именем и URI пространства имён.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Return Value

Указанный [XmlAttribute](../../xmlattribute/) или **nullptr**, если соответствующий атрибут не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttribute](../../xmlattribute/)
* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)