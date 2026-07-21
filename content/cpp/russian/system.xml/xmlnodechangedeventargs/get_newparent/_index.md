---
title: get_NewParent()
second_title: Справочник API Aspose.Slides для C++
description: "Возвращает значение XmlNode::get_ParentNode после завершения операции."
type: docs
weight: 40
url: /ru/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() метод

Возвращает значение [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) после завершения операции.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Возвращаемое значение

Значение **ParentNode** после завершения операции. Этот метод возвращает **nullptr**, если узел удаляется. Для узлов-атрибутов этот метод возвращает значение [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNodeChangedEventArgs](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)