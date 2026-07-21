---
title: ValidateAttribute()
second_title: Aspose.Slides для C++ справочника API
description: Проверяет имя атрибута, URI пространства имён и значение в текущем контексте элемента.
type: docs
weight: 144
url: /ru/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Проверяет имя атрибута, URI пространства имён и значение в текущем контексте элемента.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута для проверки. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имён атрибута для проверки. |
| attributeValue | const [String](../../../system/string/)\& | Значение атрибута для проверки. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке атрибута. Этот параметр может быть **nullptr**. |

### Возвращаемое значение

Значение проверенного атрибута.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Проверяет имя атрибута, URI пространства имён и значение в текущем контексте элемента.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута для проверки. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имён атрибута для проверки. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Обратный вызов XmlValueGetter, используемый для передачи значения атрибута как типа, совместимого с типом XML [Schema](../../) Definition Language (XSD) атрибута. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке атрибута. Этот параметр может быть **nullptr**. |

### Возвращаемое значение

Значение проверенного атрибута.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)