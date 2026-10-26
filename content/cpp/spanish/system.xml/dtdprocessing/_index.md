---
title: DtdProcessing
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica las opciones para procesar DTDs. La enumeración DtdProcessing es utilizada por la clase XmlReaderSettings.
type: docs
weight: 638
url: /es/system.xml/dtdprocessing/
---
## DtdProcessing enum

Especifica las opciones para procesar DTDs. La enumeración DtdProcessing es utilizada por la clase [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Prohibit | 0 | Especifica que cuando se encuentra un DTD, se lanza una XmlException con un mensaje que indica que los DTD están prohibidos. Este es el comportamiento predeterminado. |
| Ignore | 1 | Hace que el elemento DOCTYPE sea ignorado. No se realiza procesamiento de DTD y el DTD/DOCTYPE se pierde en la salida. |
| Parse | 2 | Se utiliza para analizar DTDs. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)