---
title: ValueAs()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het item als het opgegeven type.
type: docs
weight: 131
url: /nl/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) methode

Retourneert de waarde van het item als het opgegeven type.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het type waarin de waarde van het item moet worden geretourneerd. |

### Retourwaarde

De waarde van het item als het gevraagde type.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) methode

Wanneer overschreven in een afgeleide klasse, retourneert de waarde van het item als het opgegeven type met behulp van het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-object dat wordt gebruikt om namespace-prefixen op te lossen.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het type waarin de waarde van het item moet worden geretourneerd. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-object dat wordt gebruikt om namespace-prefixen op te lossen. |

### Retourwaarde

De waarde van het item als het gevraagde type.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XPathItem](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)