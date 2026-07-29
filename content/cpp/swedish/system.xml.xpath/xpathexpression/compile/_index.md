---
title: Compile()
second_title: Aspose.Slides för C++ API-referens
description: Kompilerar det angivna XPath-uttrycket och returnerar ett XPathExpression-objekt som representerar XPath-uttrycket.
type: docs
weight: 66
url: /sv/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metod

Kompilerar det angivna [XPath](../../)-uttrycket och returnerar ett [XPathExpression](../)-objekt som representerar [XPath](../../)-uttrycket.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ett [XPath](../../)-uttryck. |

### Returvärde

Ett [XPathExpression](../)-objekt.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metod

Kompilerar det specificerade [XPath](../../)-uttrycket, med det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet för namnrymdslösning, och returnerar ett [XPathExpression](../)-objekt som representerar [XPath](../../)-uttrycket.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ett [XPath](../../)-uttryck. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ett objekt som implementerar [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-gränssnittet för namnrymdslösning. |

### Returvärde

Ett [XPathExpression](../)-objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathExpression](../)
* Klass [String](../../../system/string/)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)