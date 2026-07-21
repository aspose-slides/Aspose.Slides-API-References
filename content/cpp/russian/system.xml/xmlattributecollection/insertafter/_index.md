---
title: InsertAfter()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет указанный атрибут непосредственно после указанного справочного атрибута.
type: docs
weight: 66
url: /ru/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) метод

Вставляет указанный атрибут сразу после указанного атрибута-ссылки.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Атрибут для вставки. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Справочный атрибут. **newNode** размещается после **refNode**. |

### Возвращаемое значение

Объект [XmlAttribute](../../xmlattribute/) для вставки в коллекцию.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlAttribute](../../xmlattribute/)
* Класс [XmlAttributeCollection](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)