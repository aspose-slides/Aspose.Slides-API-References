---
title: WriteStartElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y el prefijo dados.
type: docs
weight: 235
url: /es/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) método

Escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y el prefijo proporcionados.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del espacio de nombres del elemento. |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres que se asociará con el elemento. Si este espacio de nombres ya está en el alcance y tiene un prefijo asociado, el escritor escribe automáticamente también ese prefijo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)