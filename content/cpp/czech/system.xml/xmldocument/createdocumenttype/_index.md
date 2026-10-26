---
title: CreateDocumentType()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací nový objekt XmlDocumentType.
type: docs
weight: 313
url: /cs/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String&, const String&, const String&, const String&) metoda


Vrací nový objekt [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název typu dokumentu. |
| publicId | const [String](../../../system/string/)\& | Veřejný identifikátor typu dokumentu nebo **nullptr**. Můžete zadat veřejnou URI a také systémový identifikátor, který určuje umístění externího podmnožiny DTD. |
| systemId | const [String](../../../system/string/)\& | Systémový identifikátor typu dokumentu nebo **nullptr**. Udává URL umístění souboru pro externí podmnožinu DTD. |
| internalSubset | const [String](../../../system/string/)\& | Interní podmnožina DTD typu dokumentu nebo **nullptr**. |

### Návratová hodnota

Nový [XmlDocumentType](../../xmldocumenttype/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlDocumentType](../../xmldocumenttype/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)