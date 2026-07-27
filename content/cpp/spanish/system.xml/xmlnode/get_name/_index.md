---
title: get_Name()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada.
type: docs
weight: 1
url: /es/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() método

Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### Valor devuelto

El nombre calificado del nodo.

## Observaciones

El nombre devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo:

| Tipo | Nombre |
| --- | --- |
| [Attribute](../../../system/attribute/)| El nombre calificado del atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | El nombre del tipo de documento. |
| Element | El nombre calificado del elemento. |
| Entity | El nombre de la entidad. |
| EntityReference | El nombre de la entidad referenciada. |
| Notation | El nombre de la notación. |
| ProcessingInstruction | El objetivo de la instrucción de procesamiento. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNode](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)