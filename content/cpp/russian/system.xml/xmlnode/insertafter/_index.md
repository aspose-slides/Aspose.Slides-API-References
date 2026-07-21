---
title: InsertAfter()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет указанный узел сразу после указанного узла-ссылки.
type: docs
weight: 391
url: /ru/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) метод

Вставляет указанный узел сразу после указанного узла-ссылки.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Узел для вставки. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Узел-ссылка. **newChild** размещается после **refChild**. |

### Возвращаемое значение

Вставляемый узел.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)