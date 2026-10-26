---
title: XmlOutputMethod
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica el método usado para serializar la salida XmlWriter.
type: docs
weight: 846
url: /es/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

Especifica el método usado para serializar la salida [XmlWriter](../xmlwriter/).

```cpp
enum class XmlOutputMethod
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Xml | 0 | Serializa de acuerdo con las reglas XML 1.0. |
| Html | 1 | Serializa de acuerdo con las reglas HTML especificadas por XSLT. |
| Text | 2 | Serializa solo bloques de texto. |
| AutoDetect | 3 | Usa las reglas XSLT para elegir entre los métodos de salida [XmlOutputMethod::Xml](./) y [XmlOutputMethod::Html](./) en tiempo de ejecución. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)