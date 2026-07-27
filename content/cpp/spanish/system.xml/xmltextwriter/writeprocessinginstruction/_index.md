---
title: WriteProcessingInstruction()
second_title: Referencia de API de Aspose.Slides para C++
description: "Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto como sigue: <?name text?>."
type: docs
weight: 326
url: /es/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) método

Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la instrucción de procesamiento. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) para incluir en la instrucción de procesamiento. |

## Observaciones

Este método se está utilizando para crear una declaración XML después de que [XmlTextWriter::WriteStartDocument](../writestartdocument/) ya haya sido llamado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)