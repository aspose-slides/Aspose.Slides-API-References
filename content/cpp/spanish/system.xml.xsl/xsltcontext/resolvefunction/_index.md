---
title: ResolveFunction()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, resuelve una referencia de función y devuelve un IXsltContextFunction que representa la función. El IXsltContextFunction se utiliza en tiempo de ejecución para obtener el valor de retorno de la función.
type: docs
weight: 27
url: /es/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) method


Cuando se sobrescribe en una clase derivada, resuelve una referencia de función y devuelve un [IXsltContextFunction](../../ixsltcontextfunction/) que representa la función. El [IXsltContextFunction](../../ixsltcontextfunction/) se utiliza en tiempo de ejecución para obtener el valor de retorno de la función.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de la función tal como aparece en la expresión [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | El nombre de la función. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Una matriz de tipos de argumento para la función que se está resolviendo. Esto permite seleccionar entre métodos con el mismo nombre (por ejemplo, métodos sobrecargados). |

### Valor de retorno

Un [IXsltContextFunction](../../ixsltcontextfunction/) que representa la función.

## Ver también

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)