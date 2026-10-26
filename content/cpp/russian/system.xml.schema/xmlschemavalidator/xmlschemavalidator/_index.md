---
title: XmlSchemaValidator()
second_title: Aspose.Slides для C++ API Справочник
description: Инициализирует новый экземпляр класса XmlSchemaValidator.
type: docs
weight: 92
url: /ru/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Инициализирует новый экземпляр класса [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Объект [XmlNameTable](../../../system.xml/xmlnametable/), содержащий имена элементов и атрибутов в виде атомизированных строк. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Объект [XmlSchemaSet](../../xmlschemaset/), содержащий схемы XML [Schema](../../) Definition Language (XSD), используемые для проверки. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения пространств имён, встречающихся при проверке. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Значение XmlSchemaValidationFlags, указывающее параметры проверки схемы. |

## См. также

* Перечисление [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNameTable](../../../system.xml/xmlnametable/)
* Класс [XmlSchemaSet](../../xmlschemaset/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XmlSchemaValidator](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)