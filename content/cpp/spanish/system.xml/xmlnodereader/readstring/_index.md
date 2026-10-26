---
title: ReadString()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido de un elemento o nodo de texto como una cadena.
type: docs
weight: 391
url: /es/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() método

Lee el contenido de un elemento o nodo de texto como una cadena.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Valor devuelto

El contenido del elemento o nodo similar a texto (Esto puede incluir CDATA, [Text](../../../system.text/) nodos, y así sucesivamente). Esto puede ser una cadena vacía si el lector está posicionado en algo que no sea un elemento o nodo de texto, o si no hay más contenido de texto que devolver en el contexto actual. Nota: El nodo de texto puede ser un elemento o un nodo de texto de atributo.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)