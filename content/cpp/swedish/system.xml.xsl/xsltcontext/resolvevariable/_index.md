---
title: ResolveVariable()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, löser den en variabelreferens och returnerar en IXsltContextVariable som representerar variabeln.
type: docs
weight: 14
url: /sv/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) metod

När den åsidosätts i en avledd klass, löser den en variabelreferens och returnerar en [IXsltContextVariable](../../ixsltcontextvariable/) som representerar variabeln.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefixet för variabeln som det visas i [XPath](../../../system.xml.xpath/)-uttrycket. |
| name | [String](../../../system/string/) | Namnet på variabeln. |

### Returvärde

En [IXsltContextVariable](../../ixsltcontextvariable/) som representerar variabeln vid körning.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IXsltContextVariable](../../ixsltcontextvariable/)
* Klass [String](../../../system/string/)
* Klass [XsltContext](../)
* Namnrymd [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)