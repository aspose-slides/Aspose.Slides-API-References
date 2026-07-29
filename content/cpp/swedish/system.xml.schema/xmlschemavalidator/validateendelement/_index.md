---
title: ValidateEndElement()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll.
type: docs
weight: 209
url: /sv/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementet. Denna parameter kan vara **nullptr**. |

### Returvärde

Det analyserade, typade textvärdet för elementet om elementet har enkelt innehåll.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


Verifierar om det angivna elementets textinnehåll är giltigt enligt dess datatyp.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementets textinnehåll. Denna parameter kan vara **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Det typade textinnehållet för elementet. |

### Returvärde

Det analyserade, typade enkla innehållet för elementet.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)