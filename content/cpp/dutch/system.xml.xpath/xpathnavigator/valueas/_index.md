---
title: ValueAs()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het huidige knooppunt als het opgegeven Type, met behulp van het IXmlNamespaceResolver-object dat is opgegeven om naamruimteprefixes op te lossen.
type: docs
weight: 378
url: /nl/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) methode

Retourneert de waarde van het huidige knooppunt als het opgegeven Type, met behulp van het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat is opgegeven om naamruimteprefixes op te lossen.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het Type waarmee de waarde van het huidige knooppunt moet worden geretourneerd. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om naamruimteprefixes op te lossen. |

### Retourwaarde

De waarde van het huidige knooppunt als het aangevraagde Type.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathNavigator](../)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)