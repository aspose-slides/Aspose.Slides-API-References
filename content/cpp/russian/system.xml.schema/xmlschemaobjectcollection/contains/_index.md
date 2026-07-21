---
title: Contains()
second_title: Aspose.Slides для C++ справка API
description: Указывает, находится ли указанный XmlSchemaObject в XmlSchemaObjectCollection.
type: docs
weight: 92
url: /ru/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) метод

Указывает, находится ли указанный [XmlSchemaObject](../../xmlschemaobject/) в [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Элемент [XmlSchemaObject](../../xmlschemaobject/). |

### Возвращаемое значение

**true** если указанный квалифицированный имя находится в коллекции; в противном случае возвращает **false**. Если передан **nullptr**, возвращается **false**, потому что нет квалифицированного имени с нулевым именем.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchemaObject](../../xmlschemaobject/)
* Класс [XmlSchemaObjectCollection](../)
* Пространство имён [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)