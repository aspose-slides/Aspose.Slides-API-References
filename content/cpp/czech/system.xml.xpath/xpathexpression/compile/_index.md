---
title: Compile()
second_title: Aspose.Slides pro rozhraní API C++
description: Zkompiluje zadaný výraz XPath a vrátí objekt XPathExpression představující výraz XPath.
type: docs
weight: 66
url: /cs/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metoda


Zkompiluje zadaný výraz [XPath](../../) a vrátí objekt [XPathExpression](../) představující výraz [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../). |

### Návratová hodnota

Objekt [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metoda


Zkompiluje zadaný výraz [XPath](../../) s objektem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) určeným pro řešení jmenných prostorů a vrátí objekt [XPathExpression](../) představující výraz [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Objekt implementující rozhraní [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) pro řešení jmenných prostorů. |

### Návratová hodnota

Objekt [XPathExpression](../).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathExpression](../)
* Třída [String](../../../system/string/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)