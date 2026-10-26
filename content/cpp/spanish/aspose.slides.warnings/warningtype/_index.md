---
title: WarningType
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un tipo de advertencia.
type: docs
weight: 92
url: /es/aspose.slides.warnings/warningtype/
---
## enum WarningType

Representa un tipo de advertencia.

```cpp
enum class WarningType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SourceFileCorruption | 0 | Se ha detectado un problema en el documento de origen que hace muy probable que el documento no pueda abrirse si se guarda en su formato original. |
| DataLoss | 1 | El texto/diagrama/imagen u otros datos faltarán completamente del árbol del documento después de la carga, o del documento creado después de guardarlo. |
| MajorFormattingLoss | 2 | Pérdida importante de formato. |
| MinorFormattingLoss | 3 | Pérdida menor de formato. |
| CompatibilityIssue | 4 | Este es un problema conocido que impedirá que el documento sea abierto por ciertos agentes de usuario, o por versiones anteriores de los agentes de usuario. |
| UnexpectedContent | 99 | Algún contenido del documento de origen no pudo ser reconocido (es decir, no es compatible), lo que puede o no causar problemas o resultar en pérdida de datos/formato. |

## Ver también

* Espacio de nombres [Aspose::Slides::Warnings](../)
* Biblioteca [Aspose.Slides](../../)