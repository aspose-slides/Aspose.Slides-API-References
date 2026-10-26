---
title: ValidateEndElement()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de tekstinhoud van het element geldig is volgens het gegeven datatype voor elementen met eenvoudige inhoud, en controleert of de inhoud van het huidige element compleet is voor elementen met complexe inhoud.
type: docs
weight: 209
url: /nl/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method

Controleert of de tekstinhoud van het element geldig is volgens het gegeven datatype voor elementen met eenvoudige inhoud, en controleert of de inhoud van het huidige element volledig is voor elementen met complexe inhoud.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld na succesvolle validatie van het element. Deze parameter kan **nullptr** zijn. |

### Retourwaarde

De geparseerde, getypte tekstwaarde van het element als het element eenvoudige inhoud heeft.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method

Controleert of de tekstinhoud van het opgegeven element geldig is volgens het gegeven datatype.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld na succesvolle validatie van de tekstinhoud van het element. Deze parameter kan **nullptr** zijn. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | De getypte tekstinhoud van het element. |

### Retourwaarde

De geparseerde, getypte eenvoudige inhoud van het element.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlSchemaInfo](../../xmlschemainfo/)
* Klasse [XmlSchemaValidator](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)