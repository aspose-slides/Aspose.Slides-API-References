---
title: WarningType
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un tipo di avviso.
type: docs
url: /it/com.aspose.slides/warningtype/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Rappresenta un tipo di avviso.
## Campi

| Campo | Descrizione |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | È stato rilevato un problema nel documento sorgente che rende molto probabile che il documento non possa essere aperto se salvato nel suo formato originale. |
| [DataLoss](#DataLoss) | Testo/grafico/immagine o altri dati saranno completamente mancanti sia dall'albero del documento dopo il caricamento, sia dal documento creato dopo il salvataggio. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Perdita di formattazione maggiore. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Perdita di formattazione minore. |
| [CompatibilityIssue](#CompatibilityIssue) | Questo è un problema noto che impedirà l'apertura del documento da parte di alcuni agenti utente, o versioni precedenti di agenti utente. |
| [UnexpectedContent](#UnexpectedContent) | Alcuni contenuti nel documento sorgente non sono stati riconosciuti (ad es.) |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

È stato rilevato un problema nel documento sorgente che rende molto probabile che il documento non possa essere aperto se salvato nel suo formato originale.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Testo/grafico/immagine o altri dati saranno completamente mancanti sia dall'albero del documento dopo il caricamento, sia dal documento creato dopo il salvataggio.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Perdita di formattazione maggiore.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Perdita di formattazione minore.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Questo è un problema noto che impedirà l'apertura del documento da parte di alcuni agenti utente, o versioni precedenti di agenti utente.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Alcuni contenuti nel documento sorgente non sono stati riconosciuti (cioè non sono supportati), questo può o non può causare problemi o comportare perdita di dati/formattazione.