---
title: get_BaseURI()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el Identificador Uniforme de Recursos (URI) base del nodo.
type: docs
weight: 183
url: /es/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() método


Devuelve el Identificador Uniforme de Recursos (URI) base del nodo.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Valor devuelto

La ubicación desde la que se cargó el nodo o [String::Empty](../../../system/string/empty/) si el nodo no tiene URI base. Los nodos [Attribute](../../../system/attribute/) tienen el mismo URI base que su elemento propietario. Si un nodo de atributo no tiene un elemento propietario, get_BaseURI devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlAttribute](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)