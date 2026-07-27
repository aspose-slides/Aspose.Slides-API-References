---
title: Invoke()
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona el método para invocar la función con los argumentos dados en el contexto especificado.
type: docs
weight: 53
url: /es/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) método

Proporciona el método para invocar la función con los argumentos proporcionados en el contexto dado.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | El contexto XSLT para la llamada a la función. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Los argumentos de la llamada a la función. Cada argumento es un elemento del arreglo. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | El nodo de contexto para la llamada a la función. |

### Valor de retorno

Un [Object](../../../system/object/) que representa el valor devuelto de la función.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Object](../../../system/object/)
* Clase [XsltContext](../../xsltcontext/)
* Clase [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Clase [IXsltContextFunction](../)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)