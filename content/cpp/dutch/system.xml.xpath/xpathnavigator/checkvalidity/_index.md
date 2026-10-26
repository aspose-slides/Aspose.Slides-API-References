---
title: CheckValidity()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert dat de XML-gegevens in de XPathNavigator voldoen aan de XML Schema-definitietaal (XSD) schema dat is opgegeven.
type: docs
weight: 755
url: /nl/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

Verifieert dat de XML-gegevens in de [XPathNavigator](../) voldoen aan de XML [Schema](../../../system.xml.schema/) definitietaal (XSD) schema die is opgegeven.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | De XmlSchemaSet die de schemas bevat die worden gebruikt om de XML-gegevens te valideren die zich in de [XPathNavigator](../) bevinden. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | De ValidationEventHandler die informatie ontvangt over waarschuwingen en fouten bij het valideren van het schema. |

### Retourwaarde

**true** als er geen fouten bij schema-validatie zijn opgetreden; anders **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Klasse [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Klasse [XPathNavigator](../)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)