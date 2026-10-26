---
title: ValidateEndElement()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, является ли текстовое содержимое элемента действительным в соответствии с его типом данных для элементов с простым содержимым, и проверяет, завершено ли содержимое текущего элемента для элементов со сложным содержимым.
type: docs
weight: 209
url: /ru/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) метод

Проверяет, является ли текстовое содержимое элемента действительным в соответствии с его типом данных для элементов с простым содержимым, и проверяет, завершено ли содержимое текущего элемента для элементов со сложным содержимым.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке элемента. Этот параметр может быть **nullptr**. |

### Возвращаемое значение

Разобранное типизированное текстовое значение элемента, если элемент имеет простое содержимое.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) метод

Проверяет, является ли текстовое содержимое указанного элемента действительным в соответствии с его типом данных.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке текстового содержимого элемента. Этот параметр может быть **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Типизированное текстовое содержимое элемента. |

### Возвращаемое значение

Разобранное типизированное простое содержимое элемента.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [XmlSchemaInfo](../../xmlschemainfo/)
* Класс [XmlSchemaValidator](../)
* Пространство имён [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)