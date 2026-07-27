---
title: WriteProcessingInstruction()
second_title: Referencia API de Aspose.Slides para C++
description: "Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: <?name text?>."
type: docs
weight: 196
url: /es/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) método

Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre de la instrucción de procesamiento. |
| text | [String](../../../system/string/) | El texto a incluir en la instrucción de procesamiento. |

## Observaciones

Este método se utiliza para crear una declaración XML después de que [XmlWriter::WriteStartDocument](../writestartdocument/) ya haya sido llamado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)