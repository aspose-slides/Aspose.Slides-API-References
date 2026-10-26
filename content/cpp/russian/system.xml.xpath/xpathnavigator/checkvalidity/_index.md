---
title: CheckValidity()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, что XML-данные в XPathNavigator соответствуют предоставленной схеме языка определения XML Schema (XSD).
type: docs
weight: 755
url: /ru/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) метод

Проверяет, что XML-данные в [XPathNavigator](../) соответствуют схеме языка определения XML [Schema](../../../system.xml.schema/) (XSD), предоставленной.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet, содержащий схемы, используемые для проверки XML-данных, содержащихся в [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler, получающий информацию о предупреждениях и ошибках проверки схемы. |

## Возвращаемое значение

**true**, если ошибок проверки схемы не возникло; иначе — **false**.

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Класс [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Класс [XPathNavigator](../)
* Пространство имен [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)