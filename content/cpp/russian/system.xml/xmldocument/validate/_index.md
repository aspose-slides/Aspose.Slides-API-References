---
title: Validate()
second_title: Справочная документация API Aspose.Slides для C++
description: "Проверяет XmlDocument против схем XML Schema Definition Language (XSD), содержащихся в списке XmlDocument::get_Schemas."
type: docs
weight: 573
url: /ru/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) метод

Проверяет [XmlDocument](../) против XML [Schema](../../../system.xml.schema/) Definition Language (XSD) схем, содержащихся в списке [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Объект [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), который получает информацию о предупреждениях и ошибках проверки схемы. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) метод

Проверяет указанный объект [XmlNode](../../xmlnode/) против XML [Schema](../../../system.xml.schema/) Definition Language (XSD) схем в списке [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Объект [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), который получает информацию о предупреждениях и ошибках проверки схемы. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Объект [XmlNode](../../xmlnode/), созданный из [XmlDocument](../) для проверки. |

## См. также

* Тип [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlDocument](../)
* Класс [XmlNode](../../xmlnode/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)