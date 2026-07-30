---
title: ResolveVariable()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, risolve un riferimento a una variabile e restituisce un IXsltContextVariable che rappresenta la variabile.
type: docs
weight: 14
url: /it/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) method


Quando viene sovrascritto in una classe derivata, risolve un riferimento a una variabile e restituisce un [IXsltContextVariable](../../ixsltcontextvariable/) che rappresenta la variabile.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso della variabile così come appare nell'espressione [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Il nome della variabile. |

### Valore di ritorno

Un [IXsltContextVariable](../../ixsltcontextvariable/) che rappresenta la variabile in fase di esecuzione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXsltContextVariable](../../ixsltcontextvariable/)
* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)