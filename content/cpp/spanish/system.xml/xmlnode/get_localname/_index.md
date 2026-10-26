---
title: get_LocalName()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el nombre local del nodo, cuando se sobrescribe en una clase derivada.
type: docs
weight: 209
url: /es/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() método


Devuelve el nombre local del nodo, cuando se sobrescribe en una clase derivada.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Valor de retorno

El nombre del nodo con el prefijo eliminado. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**.

## Observaciones



El nombre devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo: 

| Tipo | Nombre |
| --- | --- |
| [Attribute](../../../system/attribute/)| El nombre local del atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | El nombre del tipo de documento. |
| Element | El nombre local del elemento. |
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