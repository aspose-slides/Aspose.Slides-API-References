---
title: PreserveWhitespace()
second_title: Referencia API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, evalúa si se deben conservar los nodos de espacio en blanco o eliminarlos para el contexto dado.
type: docs
weight: 40
url: /es/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) método


Cuando se sobrescribe en una clase derivada, evalúa si se deben conservar los nodos de espacio en blanco o eliminarlos para el contexto dado.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | El nodo de espacio en blanco que debe conservarse o eliminarse en el contexto actual. |

### Valor devuelto

**true** si el espacio en blanco debe conservarse; **false** si el espacio en blanco debe eliminarse.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Clase [XsltContext](../)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)