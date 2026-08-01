---
title: ValueAs()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert de gevalideerde waarde van het XML-element of -attribuut als het opgegeven type met behulp van het IXmlNamespaceResolver-object dat wordt gebruikt om namespace-prefixes op te lossen.
type: docs
weight: 144
url: /nl/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) methode

Retourneert de gevalideerde waarde van het XML-element of -attribuut als het gespecificeerde type met behulp van het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om namespace-prefixes op te lossen.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Het type waarin de gevalideerde waarde van het XML-element of -attribuut moet worden geretourneerd. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om namespace-prefixes op te lossen. |

### Retourwaarde

De waarde van het gevalideerde XML-element of -attribuut als het gevraagde type.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XmlAtomicValue](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)