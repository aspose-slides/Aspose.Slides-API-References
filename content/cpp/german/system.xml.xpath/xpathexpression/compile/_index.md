---
title: Compile()
second_title: Aspose.Slides für C++ API-Referenz
description: Kompiliert den angegebenen XPath-Ausdruck und gibt ein XPathExpression-Objekt zurück, das den XPath-Ausdruck darstellt.
type: docs
weight: 66
url: /de/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) Methode

Kompiliert den angegebenen [XPath](../../) Ausdruck und gibt ein [XPathExpression](../) Objekt zurück, das den [XPath](../../) Ausdruck darstellt.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ein [XPath](../../) Ausdruck. |

### Rückgabewert

Ein [XPathExpression](../) Objekt.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) Methode

Kompiliert den angegebenen [XPath](../../) Ausdruck, wobei das angegebene [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) Objekt für die Namensauflösung verwendet wird, und gibt ein [XPathExpression](../) Objekt zurück, das den [XPath](../../) Ausdruck repräsentiert.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ein [XPath](../../) Ausdruck. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ein Objekt, das das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) Interface für die Namensauflösung implementiert. |

### Rückgabewert

Ein [XPathExpression](../) Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathExpression](../)
* Klasse [String](../../../system/string/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)