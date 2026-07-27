---
title: ReadToDescendant()
second_title: Referencia de la API de Aspose.Slides para C++
description: Avanza el XmlReader al siguiente elemento descendiente con el nombre calificado especificado.
type: docs
weight: 911
url: /es/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) método

Avanza el [XmlReader](../) al siguiente elemento descendiente con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del elemento al que desea moverse. |

### Valor devuelto

**true** si se encuentra un elemento descendiente coincidente; de lo contrario **false**. Si no se encuentra un elemento hijo coincidente, el [XmlReader](../) se posiciona en la etiqueta de cierre (el valor [XmlReader::get_NodeType](../get_nodetype/) es [XmlNodeType::EndElement](../../xmlnodetype/)) del elemento. Si el [XmlReader](../) no está posicionado en un elemento cuando se llamó a [XmlReader::ReadToDescendant(String)](./), este método devuelve **false** y la posición del [XmlReader](../) no se modifica.

## XmlReader::ReadToDescendant(String, String) método

Avanza el [XmlReader](../) al siguiente elemento descendiente con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento al que desea moverse. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento al que desea moverse. |

### Valor devuelto

**true** si se encuentra un elemento descendiente coincidente; de lo contrario **false**. Si no se encuentra un elemento hijo coincidente, el [XmlReader](../) se posiciona en la etiqueta de cierre (el valor [XmlReader::get_NodeType](../get_nodetype/) es [XmlNodeType::EndElement](../../xmlnodetype/)) del elemento. Si el [XmlReader](../) no está posicionado en un elemento cuando se llamó a [XmlReader::ReadToDescendant(String,String)](./), este método devuelve **false** y la posición del [XmlReader](../) no se modifica.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)