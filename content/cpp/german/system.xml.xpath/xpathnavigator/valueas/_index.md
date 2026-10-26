---
title: ValueAs()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den Wert des aktuellen Knotens als den angegebenen Typ zurück und verwendet das IXmlNamespaceResolver-Objekt, um Namespace-Präfixe aufzulösen.
type: docs
weight: 378
url: /de/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode

Gibt den Wert des aktuellen Knotens als den angegebenen Typ zurück und verwendet das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, um Namespace-Präfixe aufzulösen.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ, in den der Wert des aktuellen Knotens zurückgegeben werden soll. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zur Auflösung von Namespace-Präfixen verwendet wird. |

### Rückgabewert

Der Wert des aktuellen Knotens als der angeforderte Typ.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)