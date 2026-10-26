---
title: ValidateAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Valideert de attribuutnaam, namespace-URI en de waarde in de huidige elementcontext.
type: docs
weight: 144
url: /nl/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) methode


Valideert de attribuutnaam, de namespace-URI en de waarde in de huidige elementcontext.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het te valideren attribuut. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI van het te valideren attribuut. |
| attributeValue | const [String](../../../system/string/)\& | De waarde van het te valideren attribuut. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld bij succesvolle validatie van het attribuut. Deze parameter kan **nullptr** zijn. |

### Retourwaarde

De waarde van het gevalideerde attribuut.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) methode


Valideert de attribuutnaam, de namespace-URI en de waarde in de huidige elementcontext.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het te valideren attribuut. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI van het te valideren attribuut. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Een XmlValueGetter-callback die wordt gebruikt om de waarde van het attribuut door te geven als een type dat compatibel is met het XML [Schema](../../) Definition Language (XSD)-type van het attribuut. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld bij succesvolle validatie van het attribuut. Deze parameter kan **nullptr** zijn. |

### Retourwaarde

De waarde van het gevalideerde attribuut.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)