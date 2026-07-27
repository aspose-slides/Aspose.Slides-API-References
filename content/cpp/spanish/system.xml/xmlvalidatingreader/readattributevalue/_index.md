---
title: ReadAttributeValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity.
type: docs
weight: 508
url: /es/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() método


Analiza el valor del atributo en uno o más **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity** nodos.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### Valor devuelto

**true** si hay nodos para devolver. **false** si el lector no está situado en un nodo de atributo cuando se realiza la llamada inicial o si se han leído todos los valores de atributo. Un atributo vacío, como **misc=\"\"**, devuelve **true** con un único nodo cuyo valor es **[String::Empty](../../../system/string/empty/)**.

## Ver también

* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)