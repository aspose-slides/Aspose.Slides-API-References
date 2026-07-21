---
title: Initialize()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует состояние объекта XmlSchemaValidator.
type: docs
weight: 118
url: /ru/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() метод

Инициализирует состояние объекта [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) метод

Инициализирует состояние объекта [XmlSchemaValidator](../) с использованием [XmlSchemaObject](../../xmlschemaobject/), указанного для частичной валидации.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Объект [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) или [XmlSchemaType](../../xmlschematype/), используемый для инициализации контекста проверки объекта [XmlSchemaValidator](../) для частичной валидации. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchemaValidator](../)
* Класс [XmlSchemaObject](../../xmlschemaobject/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)