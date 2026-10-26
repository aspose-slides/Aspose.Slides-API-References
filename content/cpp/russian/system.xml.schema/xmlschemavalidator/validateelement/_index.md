---
title: ValidateElement()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет элемент в текущем контексте.
type: docs
weight: 131
url: /ru/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) метод


Проверяет элемент в текущем контексте.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента для проверки. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имен элемента для проверки. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке имени элемента. Этот параметр может быть **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) метод


Проверяет элемент в текущем контексте с указанными значениями атрибутов **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** и **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента для проверки. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имен элемента для проверки. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке имени элемента. Этот параметр может быть **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | Значение атрибута **xsi:Type** элемента. Этот параметр может быть **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | Значение атрибута **xsi:Nil** элемента. Этот параметр может быть **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Значение атрибута **xsi:SchemaLocation** элемента. Этот параметр может быть **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Значение атрибута **xsi:NoNamespaceSchemaLocation** элемента. Этот параметр может быть **nullptr**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaInfo](../../xmlschemainfo/)
* Класс [XmlSchemaValidator](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)