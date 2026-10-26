---
title: WarningType
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un tipo di avviso.
type: docs
url: /it/com.aspose.slides/warningtype/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Rappresenta un tipo di avviso.
## Campi

| Campo | Descrizione |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | È stato rilevato un problema nel documento sorgente che rende molto probabile che il documento non possa essere aperto se salvato nel suo formato originale. |
| [DataLoss](#DataLoss) | Il testo/grafico/immagine o altri dati saranno completamente mancanti sia dall'albero del documento dopo il caricamento, sia dal documento creato dopo il salvataggio. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Perdita di formattazione importante. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Perdita di formattazione minore. |
| [CompatibilityIssue](#CompatibilityIssue) | Questo è un problema noto che impedirà l'apertura del documento da parte di alcuni agenti utente, o di versioni precedenti degli agenti utente. |
| [UnexpectedContent](#UnexpectedContent) | Alcuni contenuti nel documento sorgente non hanno potuto essere riconosciuti (ad esempio |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

È stato rilevato un problema nel documento sorgente che rende molto probabile che il documento non possa essere aperto se salvato nel suo formato originale.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Il testo/grafico/immagine o altri dati saranno completamente mancanti sia dall'albero del documento dopo il caricamento, sia dal documento creato dopo il salvataggio.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Perdita di formattazione importante.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Perdita di formattazione minore.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Questo è un problema noto che impedirà l'apertura del documento da parte di alcuni agenti utente, o di versioni precedenti degli agenti utente.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Alcuni contenuti nel documento sorgente non hanno potuto essere riconosciuti (ad esempio non sono supportati), questo può o non può causare problemi o risultare in perdita di dati/formattazione.