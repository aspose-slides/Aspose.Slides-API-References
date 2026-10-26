---
title: InsertElementBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo elemento hermano antes del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor especificado.
type: docs
weight: 1015
url: /es/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) método

Crea un nuevo elemento hermano antes del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de espacio de nombres del nuevo elemento hijo (si lo hay). |
| localName | [String](../../../system/string/) | El nombre local del nuevo elemento hijo (si lo hay). |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del nuevo elemento hijo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| value | [String](../../../system/string/) | El valor del nuevo elemento hijo. Si [String::Empty](../../../system/string/empty/) o **nullptr** se pasan, se crea un elemento vacío. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)