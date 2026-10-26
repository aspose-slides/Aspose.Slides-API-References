---
title: CreateDocumentType()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett nytt XmlDocumentType-objekt.
type: docs
weight: 313
url: /sv/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) metod

Returnerar ett nytt [XmlDocumentType](../../xmldocumenttype/)-objekt.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på dokumenttypen. |
| publicId | const [String](../../../system/string/)\& | Den offentliga identifieraren för dokumenttypen eller **nullptr**. Du kan ange en offentlig URI och även en systemidentifierare för att identifiera platsen för den externa DTD-delmängden. |
| systemId | const [String](../../../system/string/)\& | Systemidentifieraren för dokumenttypen eller **nullptr**. Anger URL:en för filens plats för den externa DTD-delmängden. |
| internalSubset | const [String](../../../system/string/)\& | Det interna DTD-subsetet för dokumenttypen eller **nullptr**. |

### Returvärde

Det nya [XmlDocumentType](../../xmldocumenttype/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlDocumentType](../../xmldocumenttype/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)