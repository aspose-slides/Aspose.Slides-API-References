---
title: InsertAfter()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет указанный узел сразу после указанного узла-ссылки.
type: docs
weight: 222
url: /ru/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) метод

Вставляет указанный узел сразу после указанного узла-ссылки.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) для вставки. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/), являющийся узлом-ссылкой. **newChild** помещается после **refChild**. |

### Возвращаемое значение

Вставленный [XmlNode](../../xmlnode/).

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlAttribute](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)