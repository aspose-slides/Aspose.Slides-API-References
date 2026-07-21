---
title: CloneNode()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт дубликат этого узла. Узлы Notation не могут быть клонированы. Вызов этого метода у объекта XmlNotation приводит к выбросу исключения.
type: docs
weight: 118
url: /ru/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) method

Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an [XmlNotation](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. |

### Возвращаемое значение

A [XmlNode](../../xmlnode/) copy of the node from which the method is called.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)