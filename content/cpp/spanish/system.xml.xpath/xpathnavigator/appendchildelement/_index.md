---
title: AppendChildElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo nodo de elemento hijo al final de la lista de nodos hijos del nodo actual utilizando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado.
type: docs
weight: 1002
url: /es/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) método

Crea un nuevo nodo de elemento hijo al final de la lista de nodos hijos del nodo actual utilizando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de espacio de nombres del nuevo nodo de elemento hijo (si lo hay). |
| localName | [String](../../../system/string/) | El nombre local del nuevo nodo de elemento hijo (si lo hay). |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del nuevo nodo de elemento hijo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| value | [String](../../../system/string/) | El valor del nuevo nodo de elemento hijo. Si [String::Empty](../../../system/string/empty/) o **nullptr** son pasados, se crea un elemento vacío. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)