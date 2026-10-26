---
title: ResolveVariable()
second_title: Aspose.Slides pro C++ API Reference
description: Když je přepsána v odvozené třídě, vyřeší odkaz na proměnnou a vrátí IXsltContextVariable představující tuto proměnnou.
type: docs
weight: 14
url: /cs/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) metoda

When overridden in a derived class, resolves a variable reference and returns an [IXsltContextVariable](../../ixsltcontextvariable/) representing the variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona proměnné, jak se objevuje ve výrazu [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Název proměnné. |

### Návratová hodnota

[IXsltContextVariable](../../ixsltcontextvariable/) představující proměnnou za běhu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IXsltContextVariable](../../ixsltcontextvariable/)
* třída [String](../../../system/string/)
* třída [XsltContext](../)
* jmenný prostor [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)