---
title: InsertBefore()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет указанный узел сразу перед указанным ссылочным узлом.
type: docs
weight: 209
url: /ru/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) метод


Вставляет указанный узел сразу перед указанным ссылочным узлом.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) для вставки. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) является ссылочным узлом. **newChild** размещается перед этим узлом. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) вставлен.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlAttribute](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)