---
title: get_Attributes()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает объект XmlAttributeCollection, содержащий атрибуты этого узла.
type: docs
weight: 105
url: /ru/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() method


Возвращает [XmlAttributeCollection](../../xmlattributecollection/), содержащий атрибуты этого узла.

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### Возвращаемое значение

[XmlAttributeCollection](../../xmlattributecollection/), содержащий атрибуты узла. Если узел имеет тип [XmlNodeType::Element](../../xmlnodetype/), возвращаются атрибуты узла. В противном случае этот метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttributeCollection](../../xmlattributecollection/)
* Класс [XmlNode](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)