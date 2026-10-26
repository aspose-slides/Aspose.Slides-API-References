---
title: InsertBefore()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет указанный атрибут непосредственно перед указанным атрибутом-ссылкой.
type: docs
weight: 53
url: /ru/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) метод

Вставляет указанный атрибут непосредственно перед указанным атрибутом-ссылкой.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Атрибут для вставки. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Атрибут-ссылка. **newNode** размещается перед **refNode**. |

### Возвращаемое значение

[XmlAttribute](../../xmlattribute/) для вставки в коллекцию.

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttribute](../../xmlattribute/)
* Класс [XmlAttributeCollection](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)