---
title: Compile()
second_title: Aspose.Slides voor C++ API-referentie
description: Compileert de opgegeven XPath-expressie en retourneert een XPathExpression object dat de XPath-expressie representeert.
type: docs
weight: 66
url: /nl/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) methode

Compileert de [XPath](../../) expressie die is opgegeven en retourneert een [XPathExpression](../) object dat de [XPath](../../) expressie weergeeft.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Een [XPath](../../) expressie. |

### Retourwaarde

Een [XPathExpression](../) object.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) methode

Compileert de opgegeven [XPath](../../) expressie, met het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat is opgegeven voor naamruimte-resolutie, en retourneert een [XPathExpression](../) object dat de [XPath](../../) expressie weergeeft.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Een [XPath](../../) expressie. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Een object dat de [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface implementeert voor naamruimte-resolutie. |

### Retourwaarde

Een [XPathExpression](../) object.

## Zie Ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathExpression](../)
* Klasse [String](../../../system/string/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)