---
title: ReadToNextSibling()
second_title: Referencia de la API de Aspose.Slides para C++
description: Avanza el XmlReader al siguiente elemento hermano con el nombre calificado especificado.
type: docs
weight: 924
url: /es/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) método

Avanza el [XmlReader](../) al siguiente elemento hermano con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del elemento hermano al que desea moverse. |

### Valor de retorno

**true** si se encuentra un elemento hermano coincidente; de lo contrario **false**. Si no se encuentra un elemento hermano coincidente, el [XmlReader](../) se posiciona en la etiqueta de cierre (el valor [XmlReader::get_NodeType](../get_nodetype/) es [XmlNodeType::EndElement](../../xmlnodetype/)) del elemento padre.

## XmlReader::ReadToNextSibling(String, String) método

Avanza el [XmlReader](../) al siguiente elemento hermano con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento hermano al que desea moverse. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento hermano al que desea moverse. |

### Valor de retorno

**true** si se encuentra un elemento hermano coincidente; de lo contrario **false**. Si no se encuentra un elemento hermano coincidente, el [XmlReader](../) se posiciona en la etiqueta de cierre (el valor [XmlReader::get_NodeType](../get_nodetype/) es [XmlNodeType::EndElement](../../xmlnodetype/)) del elemento padre.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)