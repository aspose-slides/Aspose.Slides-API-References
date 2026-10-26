---
title: get_Value()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor de texto del nodo actual.
type: docs
weight: 79
url: /es/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() método


Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Valor devuelto

El valor devuelto depende del [XmlNodeReader::get_NodeType](../get_nodetype/) del nodo.

## Observaciones



La siguiente tabla enumera los tipos de nodo que tienen un valor que devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). 

| Tipo de nodo | Valor |
| --- | --- |
| [Attribute](../../../system/attribute/)| El valor del atributo. |
| CDATA| El contenido de la sección CDATA. |
| Comment| El contenido del comentario. |
| DocumentType| El subconjunto interno. |
| ProcessingInstruction| Todo el contenido, excluyendo el destino. |
| SignificantWhitespace| El espacio en blanco entre marcas en un modelo de contenido mixto. |
| [Text](../../../system.text/)| El contenido del nodo de texto. |
| Whitespace| El espacio en blanco entre marcas. |
| [XmlDeclaration](../../xmldeclaration/)| El contenido de la declaración. |


## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)