---
title: get_Name()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre calificado del nodo actual.
type: docs
weight: 14
url: /es/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() método

Devuelve el nombre calificado del nodo actual.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Valor devuelto

El nombre calificado del nodo actual. Por ejemplo, **Name** es **bk:book** para el elemento **<bk:book>**.

## Observaciones

El nombre devuelto depende del XmlValidatingReader::NodeType del nodo. Los siguientes tipos de nodo devuelven los valores indicados. Todos los demás tipos de nodo devuelven una cadena vacía. 

| Tipo de nodo | Nombre |
| --- | --- |
| [Attribute](../../../system/attribute/)| El nombre del atributo. |
| DocumentType| El nombre del tipo de documento. |
| Element| El nombre de la etiqueta. |
| EntityReference| El nombre de la entidad referenciada. |
| ProcessingInstruction| El objetivo de la instrucción de procesamiento. |
| [XmlDeclaration](../../xmldeclaration/)| La cadena literal `xml`. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)