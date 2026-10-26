---
title: ReadAttributeValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity.
type: docs
weight: 430
url: /es/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() método


Analiza el valor del atributo en uno o más nodos **[Text](../../../system.text/)**, **EntityReference** o **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### Valor devuelto

**true** si hay nodos para devolver. **false** si el lector no está posicionado en un nodo de atributo cuando se realiza la llamada inicial o si se han leído todos los valores del atributo. Un atributo vacío, como misc=\"\", devuelve **true** con un único nodo con un valor de [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)