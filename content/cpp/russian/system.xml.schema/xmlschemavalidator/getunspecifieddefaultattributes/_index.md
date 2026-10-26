---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides для C++ API Reference
description: "Проверяет ограничения идентичности на атрибуты по умолчанию и заполняет указанный List объектами XmlSchemaAttribute для всех атрибутов с значениями по умолчанию, которые ранее не были проверены с помощью метода XmlSchemaValidator::ValidateAttribute в контексте элемента."
type: docs
weight: 157
url: /ru/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) метод

Проверяет ограничения идентичности на атрибутах по умолчанию и заполняет указанный List объектами [XmlSchemaAttribute](../../xmlschemaattribute/) для всех атрибутов с значениями по умолчанию, которые ранее не были проверены с помощью метода [XmlSchemaValidator::ValidateAttribute](../validateattribute/) в контексте элемента.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | List для заполнения объектами [XmlSchemaAttribute](../../xmlschemaattribute/) для всех атрибутов, которые ещё не были обнаружены во время проверки в контексте элемента. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [List](../../../system.collections.generic/list/)
* Класс [Object](../../../system/object/)
* Класс [XmlSchemaValidator](../)
* Пространство имён [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)