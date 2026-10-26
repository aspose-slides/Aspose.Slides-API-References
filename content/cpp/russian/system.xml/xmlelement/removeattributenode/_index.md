---
title: RemoveAttributeNode()
second_title: Справка API Aspose.Slides для C++
description: Удаляет указанный XmlAttribute.
type: docs
weight: 274
url: /ru/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) метод


Удаляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Узел [XmlAttribute](../../xmlattribute/), который нужно удалить. Если удаляемый атрибут имеет значение по умолчанию, оно сразу заменяется. |

### Возвращаемое значение

Удалённый [XmlAttribute](../../xmlattribute/) или **nullptr**, если **oldAttr** не является узлом-атрибутом [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) метод


Удаляет [XmlAttribute](../../xmlattribute/), указанный локальным именем и URI пространства имён. (Если удаляемый атрибут имеет значение по умолчанию, оно сразу заменяется).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

Удалённый [XmlAttribute](../../xmlattribute/) или **nullptr**, если у [XmlElement](../) нет соответствующего узла-атрибута.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttribute](../../xmlattribute/)
* Класс [XmlElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)