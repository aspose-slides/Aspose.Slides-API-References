---
title: Compile()
second_title: Aspose.Slides C++ API referenciája
description: Lefordítja a megadott XPath kifejezést, és visszaad egy XPathExpression objektumot, amely a XPath kifejezést reprezentálja.
type: docs
weight: 66
url: /hu/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metódus


Lefordítja a megadott [XPath](../../) kifejezést, és visszaad egy [XPathExpression](../) objektumot, amely a [XPath](../../) kifejezést reprezentálja.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Egy [XPath](../../) kifejezés. |

### Visszatérési érték

Egy [XPathExpression](../) objektum.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metódus


Lefordítja a megadott [XPath](../../) kifejezést, a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektummal, amely a névtér feloldásához van megadva, és visszaad egy [XPathExpression](../) objektumot, amely a [XPath](../../) kifejezést reprezentálja.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Egy [XPath](../../) kifejezés. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Egy objektum, amely a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interfészt valósítja meg a névtér feloldásához. |

### Visszatérési érték

Egy [XPathExpression](../) objektum.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathExpression](../)
* Osztály [String](../../../system/string/)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)