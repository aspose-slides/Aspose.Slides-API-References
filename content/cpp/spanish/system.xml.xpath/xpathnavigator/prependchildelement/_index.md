---
title: PrependChildElement()
second_title: Aspose.Slides para C++ Referencia de API
description: Crea un nuevo elemento hijo al principio de la lista de nodos hijos del nodo actual utilizando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor especificado.
type: docs
weight: 989
url: /es/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) método

Crea un nuevo elemento secundario al principio de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de espacio de nombres del nuevo elemento secundario (si lo hay). |
| localName | [String](../../../system/string/) | El nombre local del nuevo elemento secundario (si lo hay). |
| namespaceURI | [String](../../../system/string/) | El URI de espacio de nombres del nuevo elemento secundario (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| value | [String](../../../system/string/) | El valor del nuevo elemento secundario. Si se pasa [String::Empty](../../../system/string/empty/) o **nullptr**, se crea un elemento vacío. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)