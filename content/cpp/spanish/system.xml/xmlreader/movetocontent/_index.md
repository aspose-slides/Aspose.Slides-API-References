---
title: MoveToContent()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Comprueba si el nodo actual es un nodo de contenido (texto que no es espacio en blanco, CDATA, Element, EndElement, EntityReference o EndEntity). Si el nodo no es un nodo de contenido, el lector avanza hasta el siguiente nodo de contenido o el final del archivo. Omite los nodos del siguiente tipo: ProcessingInstruction, DocumentType, Comment, Whitespace o SignificantWhitespace."
type: docs
weight: 833
url: /es/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() método

Comprueba si el nodo actual es un nodo de contenido (texto que no es espacio en blanco, **CDATA**, **Element**, **EndElement**, **EntityReference**, o **EndEntity**). Si el nodo no es un nodo de contenido, el lector avanza hasta el próximo nodo de contenido o el final del archivo. Omite los nodos del siguiente tipo: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, o **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Valor de retorno

El [XmlReader::get_NodeType](../get_nodetype/) valor del nodo actual encontrado por el método o [XmlNodeType::None](../../xmlnodetype/) si el lector ha alcanzado el final del flujo de entrada.

## Ver también

* Enum [XmlNodeType](../../xmlnodetype/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)