---
title: Compile()
second_title: Riferimento API di Aspose.Slides per C++
description: Compila l'espressione XPath specificata e restituisce un oggetto XPathExpression che rappresenta l'espressione XPath.
type: docs
weight: 66
url: /it/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method

Compila l'espressione [XPath](../../) specificata e restituisce un oggetto [XPathExpression](../) che rappresenta l'espressione [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Una [XPath](../../) espressione. |

### Valore di ritorno

Un [XPathExpression](../) oggetto.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method

Compila l'espressione [XPath](../../) specificata, con l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) specificato per la risoluzione dei namespace, e restituisce un oggetto [XPathExpression](../) che rappresenta l'espressione [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Una [XPath](../../) espressione. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un oggetto che implementa l'interfaccia [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) per la risoluzione dei namespace. |

### Valore di ritorno

Un [XPathExpression](../) oggetto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)