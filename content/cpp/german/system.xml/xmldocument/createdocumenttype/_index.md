---
title: CreateDocumentType()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein neues XmlDocumentType-Objekt zurück.
type: docs
weight: 313
url: /de/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String&, const String&, const String&, const String&) Methode

Gibt ein neues [XmlDocumentType](../../xmldocumenttype/) Objekt zurück.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Name des Dokumenttyps. |
| publicId | const [String](../../../system/string/)& | Der öffentliche Bezeichner des Dokumenttyps oder **nullptr**. Sie können eine öffentliche URI und auch einen Systembezeichner angeben, um den Ort des externen DTD-Teils zu identifizieren. |
| systemId | const [String](../../../system/string/)& | Der Systembezeichner des Dokumenttyps oder **nullptr**. Gibt die URL des Dateiorts für den externen DTD-Teil an. |
| internalSubset | const [String](../../../system/string/)& | Der interne DTD-Teil des Dokumenttyps oder **nullptr**. |

### Rückgabewert

Das neue [XmlDocumentType](../../xmldocumenttype/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDocumentType](../../xmldocumenttype/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)