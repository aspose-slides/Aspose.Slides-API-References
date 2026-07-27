---
title: get_Value()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor del nodo.
type: docs
weight: 14
url: /es/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() método


Devuelve el valor del nodo.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Valor devuelto

El valor devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo: 

| Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| El valor del atributo. |
| CDATASection | El contenido de la CDATA Section. |
| Comment | El contenido del Comment. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Puede usar XmlElement::InnerText o los valores [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) para acceder al valor del nodo de elemento. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Todo el contenido excluyendo el objetivo. |
| [Text](../../../system.text/)| El contenido del nodo de texto. |
| SignificantWhitespace | Los caracteres de espacio en blanco. El espacio en blanco puede consistir en uno o más caracteres de espacio, retornos de carro, saltos de línea o tabulaciones. |
| Whitespace | Los caracteres de espacio en blanco. El espacio en blanco puede consistir en uno o más caracteres de espacio, retornos de carro, saltos de línea o tabulaciones. |
| [XmlDeclaration](../../xmldeclaration/)| El contenido de la declaración (es decir, todo lo que está entre `<?xml y ?>`). |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNode](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)