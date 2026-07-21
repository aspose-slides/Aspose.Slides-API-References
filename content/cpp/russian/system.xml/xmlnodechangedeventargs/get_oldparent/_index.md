---
title: get_OldParent()
second_title: Справочник API Aspose.Slides для C++
description: "Возвращает значение XmlNode::get_ParentNode до начала операции."
type: docs
weight: 27
url: /ru/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() метод

Возвращает значение [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) до начала операции.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Возвращаемое значение

Значение **ParentNode** до начала операции. Этот метод возвращает **nullptr**, если у узла не было родителя. Для узлов-атрибутов этот метод возвращает значение [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNodeChangedEventArgs](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)