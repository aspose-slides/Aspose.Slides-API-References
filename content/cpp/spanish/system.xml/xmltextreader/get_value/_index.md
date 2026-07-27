---
title: get_Value()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve el valor de texto del nodo actual.
type: docs
weight: 79
url: /es/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() método

Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Valor devuelto

El valor devuelto depende del valor [XmlTextReader::get_NodeType](../get_nodetype/) del nodo.

## Observaciones

Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/).

| Tipo de nodo | Valor |
| --- | --- |
| [Attribute](../../../system/attribute/)| El valor del atributo. |
| CDATA| El contenido de la sección CDATA. |
| Comment| El contenido del comentario. |
| DocumentType| El subconjunto interno. |
| ProcessingInstruction| Todo el contenido, excluyendo el objetivo. |
| SignificantWhitespace| El espacio en blanco dentro de un ámbito `xml:space='preserve'`. |
| [Text](../../../system.text/)| El contenido del nodo de texto. |
| Whitespace| El espacio en blanco entre marcas. |
| [XmlDeclaration](../../xmldeclaration/)| El contenido de la declaración. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)