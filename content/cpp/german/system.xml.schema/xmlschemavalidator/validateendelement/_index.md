---
title: ValidateEndElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob der Textinhalt des Elements gemäß seinem Datentyp für Elemente mit einfachem Inhalt gültig ist, und prüft, ob der Inhalt des aktuellen Elements für Elemente mit komplexem Inhalt vollständig ist.
type: docs
weight: 209
url: /de/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) Methode

Überprüft, ob der Textinhalt des Elements gemäß seinem Datentyp für Elemente mit einfachem Inhalt gültig ist, und prüft, ob der Inhalt des aktuellen Elements für Elemente mit komplexem Inhalt vollständig ist.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Elements gesetzt werden. Dieser Parameter kann **nullptr** sein. |

### Rückgabewert

Der geparste, typisierte Textwert des Elements, wenn das Element einfachen Inhalt hat.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) Methode

Überprüft, ob der Textinhalt des angegebenen Elements gemäß seinem Datentyp gültig ist.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Textelements gesetzt werden. Dieser Parameter kann **nullptr** sein. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Der typisierte Textinhalt des Elements. |

### Rückgabewert

Der geparste, typisierte einfache Inhalt des Elements.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlSchemaInfo](../../xmlschemainfo/)
* Klasse [XmlSchemaValidator](../)
* Namensraum [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)