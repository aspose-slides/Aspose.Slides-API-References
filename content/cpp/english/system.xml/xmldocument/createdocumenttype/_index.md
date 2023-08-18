---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new XmlDocumentType object.
type: docs
weight: 313
url: /system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method


Returns a new [XmlDocumentType](../../xmldocumenttype/) object.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Name of the document type. |
| publicId | const [String](../../../system/string/)\& | The public identifier of the document type or **nullptr**. You can specify a public URI and also a system identifier to identify the location of the external DTD subset. |
| systemId | const [String](../../../system/string/)\& | The system identifier of the document type or **nullptr**. Specifies the URL of the file location for the external DTD subset. |
| internalSubset | const [String](../../../system/string/)\& | The DTD internal subset of the document type or **nullptr**. |

### Return Value

The new [XmlDocumentType](../../xmldocumenttype/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)