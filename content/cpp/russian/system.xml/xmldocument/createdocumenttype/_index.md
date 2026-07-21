---
title: CreateDocumentType()
second_title: Справка API Aspose.Slides для C++
description: Возвращает новый объект XmlDocumentType.
type: docs
weight: 313
url: /ru/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) метод

Возвращает новый объект [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя типа документа. |
| publicId | const [String](../../../system/string/)\& | Публичный идентификатор типа документа или **nullptr**. Вы можете указать публичный URI, а также системный идентификатор, чтобы определить расположение внешнего подмножества DTD. |
| systemId | const [String](../../../system/string/)\& | Системный идентификатор типа документа или **nullptr**. Указывает URL расположения файла для внешнего подмножества DTD. |
| internalSubset | const [String](../../../system/string/)\& | Внутреннее подмножество DTD типа документа или **nullptr**. |

### Возвращаемое значение

Новый [XmlDocumentType](../../xmldocumenttype/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlDocumentType](../../xmldocumenttype/)
* Класс [String](../../../system/string/)
* Класс [XmlDocument](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)