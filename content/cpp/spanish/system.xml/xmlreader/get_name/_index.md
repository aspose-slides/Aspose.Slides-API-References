---
title: get_Name()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene el nombre cualificado del nodo actual.
type: docs
weight: 27
url: /es/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() método

Cuando se sobrescribe en una clase derivada, obtiene el nombre cualificado del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### Valor devuelto

El nombre cualificado del nodo actual. Por ejemplo, **Name** es **bk:book** para el elemento **<bk:book>**.

## Observaciones

El nombre devuelto depende del valor [XmlReader::get_NodeType](../get_nodetype/) del nodo. Los siguientes tipos de nodo devuelven los valores listados. Todos los demás tipos de nodo devuelven una cadena vacía. 

| Tipo de nodo | Nombre |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| El nombre del atributo. |
| `DocumentType`| El nombre del tipo de documento. |
| `Element`| El nombre de la etiqueta. |
| `EntityReference`| El nombre de la entidad referenciada. |
| `ProcessingInstruction`| El objetivo de la instrucción de procesamiento. |
| [XmlDeclaration](../../xmldeclaration/)| La cadena literal `xml`. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)