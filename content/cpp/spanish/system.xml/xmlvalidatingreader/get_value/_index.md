---
title: get_Value()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve el valor de texto del nodo actual.
type: docs
weight: 79
url: /es/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() método


Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### Valor devuelto

El valor devuelto depende del XmlValidatingReader::NodeType del nodo.

## Observaciones

La tabla siguiente enumera los tipos de nodo que tienen un valor que devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). 

| Tipo de nodo | Valor |
| --- | --- |
| [Attribute](../../../system/attribute/)| El valor del atributo. |
| CDATA| El contenido de la sección CDATA. |
| Comment| El contenido del comentario. |
| DocumentType| El subconjunto interno. |
| ProcessingInstruction| Todo el contenido, excluyendo el objetivo. |
| SignificantWhitespace| El espacio en blanco entre marcado en un modelo de contenido mixto. |
| [Text](../../../system.text/)| El contenido del nodo de texto. |
| Whitespace| El espacio en blanco entre marcado. |
| [XmlDeclaration](../../xmldeclaration/)| El contenido de la declaración. |


## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)