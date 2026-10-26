---
title: CreateDocumentType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca nowy obiekt XmlDocumentType.
type: docs
weight: 313
url: /pl/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method


Zwraca nowy [XmlDocumentType](../../xmldocumenttype/) object.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa typu dokumentu. |
| publicId | const [String](../../../system/string/)\& | Publiczny identyfikator typu dokumentu lub **nullptr**. Można podać publiczny URI oraz identyfikator systemowy określający lokalizację zewnętrznego podzbioru DTD. |
| systemId | const [String](../../../system/string/)\& | Identyfikator systemowy typu dokumentu lub **nullptr**. Określa URL lokalizacji pliku zewnętrznego podzbioru DTD. |
| internalSubset | const [String](../../../system/string/)\& | Wewnętrzny podzbiór DTD typu dokumentu lub **nullptr**. |

### Return Value

Nowy [XmlDocumentType](../../xmldocumenttype/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)