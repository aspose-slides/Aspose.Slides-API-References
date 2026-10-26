---
title: ReadAttributeValue()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity.
type: docs
weight: 677
url: /es/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() método


Cuando se sobrescribe en una clase derivada, analiza el valor del atributo en uno o más nodos **[Text](../../../system.text/)**, **EntityReference** o **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Valor devuelto

**true** si hay nodos para devolver. **false** si el lector no está posicionado en un nodo de atributo cuando se realiza la llamada inicial o si se han leído todos los valores de atributo. Un atributo vacío, como **misc=\"\"**, devuelve **true** con un solo nodo con un valor de [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)