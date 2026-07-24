---
title: ResolveVariable()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, löst sie eine Variablenreferenz auf und gibt ein IXsltContextVariable zurück, das die Variable darstellt.
type: docs
weight: 14
url: /de/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, löst sie eine Variablenreferenz auf und gibt ein [IXsltContextVariable](../../ixsltcontextvariable/) zurück, das die Variable darstellt.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der Präfix der Variable, wie er im [XPath](../../../system.xml.xpath/) Ausdruck erscheint. |
| name | [String](../../../system/string/) | Der Name der Variable. |

### Rückgabewert

Ein [IXsltContextVariable](../../ixsltcontextvariable/), das die Variable zur Laufzeit darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXsltContextVariable](../../ixsltcontextvariable/)
* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)