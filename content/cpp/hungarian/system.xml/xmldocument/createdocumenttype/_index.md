---
title: CreateDocumentType()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy új XmlDocumentType objektumot.
type: docs
weight: 313
url: /hu/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) metódus

Visszaad egy új [XmlDocumentType](../../xmldocumenttype/) objektumot.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A dokumentumtípus neve. |
| publicId | const [String](../../../system/string/)\& | A dokumentumtípus nyilvános azonosítója vagy **nullptr**. Megadhat egy nyilvános URI-t, valamint egy rendszerazonosítót is, amely azonosítja a külső DTD részhalmaz helyét. |
| systemId | const [String](../../../system/string/)\& | A dokumentumtípus rendszerazonosítója vagy **nullptr**. Meghatározza a külső DTD részhalmaz fájlhelyének URL-jét. |
| internalSubset | const [String](../../../system/string/)\& | A dokumentumtípus DTD belső részhalmaza vagy **nullptr**. |

### Visszatérési érték

Az új [XmlDocumentType](../../xmldocumenttype/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlDocumentType](../../xmldocumenttype/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)