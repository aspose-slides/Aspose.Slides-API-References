---
title: SetAttributeNode()
second_title: Aspose.Slides для C++ справка по API
description: Добавляет указанный XmlAttribute.
type: docs
weight: 261
url: /ru/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) метод

Добавляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Узел [XmlAttribute](../../xmlattribute/) для добавления в коллекцию атрибутов этого элемента. |

### Возвращаемое значение

Если атрибут заменяет существующий атрибут с тем же именем, возвращается старый [XmlAttribute](../../xmlattribute/); в противном случае возвращается **nullptr**.

## XmlElement::SetAttributeNode(String, String) метод

Добавляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

[XmlAttribute](../../xmlattribute/) для добавления.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)