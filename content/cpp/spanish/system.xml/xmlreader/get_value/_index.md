---
title: get_Value()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual.
type: docs
weight: 92
url: /es/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() método

Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Valor devuelto

El valor devuelto depende del valor [XmlReader::get_NodeType](../get_nodetype/) del nodo.

## Observaciones

La tabla siguiente enumera los tipos de nodo que tienen un valor que devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). 

| Tipo de nodo | Valor |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| El valor del atributo. |
| `CDATA`| El contenido de la sección CDATA. |
| `Comment`| El contenido del comentario. |
| `DocumentType`| El subconjunto interno. |
| `ProcessingInstruction`| Todo el contenido, excluyendo el destino. |
| `SignificantWhitespace`| El espacio en blanco entre marcas en un modelo de contenido mixto. |
| `[Text](../../../system.text/)`| El contenido del nodo de texto. |
| `Whitespace`| El espacio en blanco entre marcas. |
| [XmlDeclaration](../../xmldeclaration/)| El contenido de la declaración. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)