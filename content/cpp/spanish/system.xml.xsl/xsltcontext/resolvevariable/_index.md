---
title: ResolveVariable()
second_title: Aspose.Slides para la referencia de la API de C++
description: Cuando se sobrescribe en una clase derivada, resuelve una referencia a una variable y devuelve un IXsltContextVariable que representa la variable.
type: docs
weight: 14
url: /es/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) método

Cuando se sobrescribe en una clase derivada, resuelve una referencia a una variable y devuelve un [IXsltContextVariable](../../ixsltcontextvariable/) que representa la variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de la variable tal como aparece en la expresión [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | El nombre de la variable. |

### Valor devuelto

Un [IXsltContextVariable](../../ixsltcontextvariable/) que representa la variable en tiempo de ejecución.

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IXsltContextVariable](../../ixsltcontextvariable/)
* Clase [String](../../../system/string/)
* Clase [XsltContext](../)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)