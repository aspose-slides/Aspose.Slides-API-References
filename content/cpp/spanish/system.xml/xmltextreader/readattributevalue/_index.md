---
title: ReadAttributeValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity.
type: docs
weight: 560
url: /es/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() method

Analiza el valor del atributo en uno o más **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity** nodos.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Valor de retorno

**true** si hay nodos para devolver. **false** si el lector no está posicionado en un nodo de atributo cuando se realiza la llamada inicial o si se han leído todos los valores de atributo. Un atributo vacío, como **misc=\"\"**, devuelve **true** con un único nodo con un valor de [String::Empty](../../../system/string/empty/).

## Véase también

* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)