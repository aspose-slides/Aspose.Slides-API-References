---
title: InsertBefore()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет указанный узел непосредственно перед указанным узлом-ссылкой.
type: docs
weight: 378
url: /ru/system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) метод

Вставляет указанный узел непосредственно перед указанным узлом-ссылкой.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Узел для вставки. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Узел-ссылка. **newChild** размещается перед этим узлом. |

### Возвращаемое значение

Вставляемый узел.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)