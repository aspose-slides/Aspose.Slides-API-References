---
title: WarningType
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un tipo de advertencia.
type: docs
url: /es/com.aspose.slides/warningtype/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Representa un tipo de advertencia.
## Campos

| Campo | Descripción |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Se ha detectado un problema en el documento fuente que hace muy probable que el documento no pueda abrirse si se guarda en su formato original. |
| [DataLoss](#DataLoss) | El texto, gráfico, imagen u otros datos estarán completamente ausentes del árbol del documento después de cargarlo, o del documento creado después de guardarlo. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Pérdida importante de formato. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Pérdida menor de formato. |
| [CompatibilityIssue](#CompatibilityIssue) | Este es un problema conocido que impedirá que el documento sea abierto por ciertos agentes de usuario, o versiones anteriores de agentes de usuario. |
| [UnexpectedContent](#UnexpectedContent) | Algún contenido en el documento fuente no pudo ser reconocido (p. ej. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Se ha detectado un problema en el documento fuente que hace muy probable que el documento no pueda abrirse si se guarda en su formato original.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

El texto, gráfico, imagen u otros datos estarán completamente ausentes del árbol del documento después de cargarlo, o del documento creado después de guardarlo.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Pérdida importante de formato.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Pérdida menor de formato.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Este es un problema conocido que impedirá que el documento sea abierto por ciertos agentes de usuario, o versiones anteriores de agentes de usuario.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Algún contenido en el documento fuente no pudo ser reconocido (p. ej. no es compatible), lo que puede o no causar problemas o resultar en pérdida de datos o de formato.